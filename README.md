# Test
Test Ombio

1. 
npm install -g react-native-cli

2. 
react-native init Tharindu_Test

3.
git init

git add

git add README.md

4.
git commit -m "Freash React Native App"

git remote add origin https://github.com/SachiyaTZ/Test.git

5.
react-native run android

6.
git commit -m "SignIn component"

7.
git commit -m "SignIn component UI"

8.
git commit -m "SignIn component validation"

git push -u origin master

9.
keytool -genkeypair -v -keystore my-upload-key.keystore -alias my-key-alias -keyalg RSA -keysize 2048 -validity 10000

MYAPP_UPLOAD_STORE_FILE=my-upload-key.keystore

MYAPP_UPLOAD_KEY_ALIAS=my-key-alias

MYAPP_UPLOAD_STORE_PASSWORD=*****

MYAPP_UPLOAD_KEY_PASSWORD=*****

react-native run-android --variant=release


10.
1. What it is

React Native:
React Native relies on React (JavaScript framework) to design the user interface using JavaScript. It supports both Android and iOS to develop hybrid apps. By default, React Native apps do not use WebViews to render the app's user interface as in Cordova. A JavaScript interpreter is rooted to execute only the app's JS code.

Cordova:
Cordova is another open source JavaScript framework for hybrid app design. Cordova apps use WebView to provide the app's user interface. Cordova also allows developers to use the latest web technologies such as HTML5, JS, etc. To design apps for Android, iOS and Windows.

2.Performance

React Native: - Apps developed using React Native are faster than Cordova apps but slower than native ones.
Cordova: - Cordova apps are just web views that make them slow and less responsive.

3. Platforms

React Native:- Android and iOS.
Cordova:- Android, iOS and Microsoft UWP.

4. Backward compatibility
React Native:-Some old platforms are working but iOS 7 not support.
Cordova:-Running old platforms.

5.Debugging

React Native: the React Native user interface is debugged in the application itself and JavaScript is debugged in the Chrome Developer Console. When debugging the native React application, the device should only be connected for the first time. Then the debugging process can be performed via LAN. Also, debugging the React Native application is simpler and simpler than debugging the Cordova application.
Cordova: - In Cordova applications, the user interface and JavaScript are debugged in the Chrome development console. The device must be connected to the system when debugging the Cordova application.

11.
No Answering

12.
Hook rules

1. Never call hooks inside a loop, condition or nested function.
2. Never call a hook from a normal function.
3. Call only hooks within function components or custom hooks.
4. The hooks should be at the beginning of the element.

So.. In I saw when react class vs reacl hooks 
We previously created a function component for reusing user interface elements quite simply. The problem arose after meeting the need for an event or life cycle, which would mean creating a class component.


