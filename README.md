<pre>
Initializing Dart VM...

Dart VM is ready to use.
To contact me, please send me a message to `<a href="mailto:ogbonnagideonofficial@gmail.com">ogbonnagideonofficial@gmail.com</a>`.
For more details, please visit <a href="https://gideonogbonna.com">https://gideonogbonna.com</a>.
MacBook-Pro:~ GiddyCode$ cat ./main.dart
</pre>

```dart
void main() {
  const websiteUrl = 'gideonogbonna.com';
  
  final me = PersonalInfo(
    title: 'Senior Software Engineer',
    contacInfo: ContactInfo(
      email: Uri.parse('mailto:ogbonnagideonofficial@gmail.com'),
      linkedIn: Uri.https('www.linkedin.com', 'in/gideonogbonna/'),
      github: Uri.https('github.com', 'gideonogbonna'),
      portfolio: Uri.https('gideonogbonna.com'),
    ),
    softwareEngineeringInfo: SoftwareEngineeringInfo(
      experienceYears: '8+',
      projectsCount: 'Many!', // And counting... :)
      // Apps published on various stores
      apps: <Store>[
        // iOS apps in the App Store
        AppStore(
          hasPublishedApps: true,
          appsCount: 4,
        ),
        // Android apps in the Play Store
        PlayStore(
          hasPublishedApps: true,
          appsCount: 6,
        ),
      ],
      architecturesAndTools: <String>[
        'Flutter',
        'React Native',
        'Kotlin',
        'Swift',
        'Objective-C',
        'Java',
        'Node.js',
        'Firebase',
        'Cloud Firestore',
        'Cloud Functions',
      ],
    ),
    otherSkills: <String>[ // The most relevant
      'UI / UX',
      'JavaScript',
      'TypeScript',
      'React',
      'NodeJS',
      'HTML / CSS',
      'Express',
    ],
    projects: <Project>[
      Project(
        'Fin.AI',
        role: 'Senior Software Engineer',
        platforms: Platforms(ios: true, android: true, web: true),
        url: Uri.https('github.com', 'gideonogbonna/Fin.AI'),
      ),
      Project(
        'Elderberry.care',
        role: 'Senior Mobile Engineer',
        platforms: Platforms(android: true, iOS: true),
      ),
      Project(
        'GladeFinance',
        role: 'Lead Mobile Application Developer',
        platforms: Platforms(android: true, iOS: true),
        url: Uri.https('github.com', 'gideonogbonna/GladeFinance'),
      ),
      Project(
        'My Mobile Portfolio',
        role: 'Senior Mobile Engineer',
        platforms: Platforms(web: true),
        url: Uri.https('gideonogbonna.com', 'portfolio'),
      ),
      Project(
        'Cashews Finance',
        role: 'Senior Mobile Engineer',
        platforms: Platforms(android: true, iOS: true),
        url: Uri.https(websiteUrl, 'cashews-finance'),
      ),
      Project(
        'Self-Service Kiosk',
        role: 'Full Stack Software Engineer',
        platforms: Platforms(android: true),
        url: Uri.https(websiteUrl, 'self-service-kiosk'),
      ),
    ],
  )..setStatus(
    learningCoolStuff: true,
    openToNewProjects: true,
  );
}

```
<pre>
MacBook-Pro:~ GiddyCode$
</pre>
  
## Apps on Stores

<a href="https://apps.apple.com/us/developer" target="_blank">iOS apps on App Store</a><br>
<a href="https://play.google.com/store/apps" target="_blank">Android apps on Play Store</a>

## Some stuff I've used

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/flutter/flutter-original.svg" title="Flutter" alt="Flutter" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/dart/dart-original.svg" title="Dart" alt="Dart" width="40" height="40"/>&nbsp;
  <img src="https://github.com/monster555/monster555/blob/main/bloc-logo.svg" title="BLoC" alt="BLoC" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/firebase/firebase-plain.svg" title="Firebase" alt="Firebase" width="40" height="40"/>&nbsp;
  <img src="https://github.com/monster555/monster555/blob/main/parse-server-logo.svg" title="Parse Server" alt="Parse Server" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/mongodb/mongodb-original.svg" title="MongoDB" **alt="MongoDB" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original.svg" title="NodeJS" alt="NodeJS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/npm/npm-original-wordmark.svg" title="NPM" alt="NPM" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/express/express-original.svg" title="Express" alt="Express" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-original.svg" title="TypeScript" alt="TypeScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/tensorflow/tensorflow-original.svg" title="TensorFlow" alt="TensorFlow" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nextjs/nextjs-original.svg" title="NextJS" alt="NextJS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/ionic/ionic-original.svg" title="Ionic" alt="Ionic" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/androidstudio/androidstudio-original.svg" title="Android Studio" alt="Android Studio" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/xcode/xcode-original.svg" title="Xcode" alt="Xcode" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/slack/slack-original.svg" title="Slack" alt="Slack" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/jira/jira-original.svg" title="Jira" alt="Jira" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>
</div>
