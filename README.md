"# globalapp" 
**
Installation **

Ref: https://reactnative.dev/docs/getting-started

Install below package and software
1. NPM : https://nodejs.org/en/download/ download  current version
2. JDK 1.8 and set path in environment variable
3. Android Studio : https://developer.android.com/studio
4. Open SDK manager : C:\Users\<computerusername>\AppData\Local\Android\Sdk
5. Provide Path in environment variable
  a)  C:\Users\<computerusername>\AppData\Local\Android\Sdk\tools
  b) C:\Users\<computerusername>\AppData\Local\Android\Sdk\platform-tools
  c) run adb --version command in command prompt
  ![image](https://user-images.githubusercontent.com/79181490/109388385-b957e800-792c-11eb-8b50-e3442ee42cc5.png)
6) Open cmd and run below react installion command 
  a) npm install -g create-react-native-app
  b) create-react-native-app MyReactNative or npx create-react-native-app MyReactNative
  c) connect device from laptop and run adb devices (device id will be display in command prompt)
  d) run npm react-native run-android 
  e) app will install in mobile and open
  
  Issue:
  a) if SDK manager error is coming then go to  C:\Users\<computerusername>\AppData\Local\Android\Sdk\tools\bin 
  b) open Command prompt and go to above location 
  c) run sdkmanager --licenses
  
  
    

