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
  c) run command sdkmanager --licenses
  
  First time app will shown react native page
  
  ![image](https://user-images.githubusercontent.com/79181490/109388806-5f0c5680-792f-11eb-89ea-a1fb5bcaa832.png)
  
  Shake the mobile and it wil show options
  
  ![image](https://user-images.githubusercontent.com/79181490/109388894-d9d57180-792f-11eb-85d5-e6443b4cee68.png)

  
  
  click the debugger and debugger will open in browser automatically
  ![image](https://user-images.githubusercontent.com/79181490/109388881-ca562880-792f-11eb-8489-46f851a1e7d1.png)


  
  
    

