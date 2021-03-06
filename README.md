"# globalapp" 

**Installation**

Ref: https://reactnative.dev/docs/getting-started

Install below package and software
1. NPM : https://nodejs.org/en/download/current/ download  current version

![image](https://user-images.githubusercontent.com/79181490/109410245-02f11300-79bf-11eb-8998-b29efe2930ec.png)

3. JDK 1.8 and set path in environment variable
4. Android Studio : https://developer.android.com/studio
5. Open SDK manager : C:\Users\<computerusername>\AppData\Local\Android\Sdk
6. Provide Path in environment variable
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
  
  ![image](https://user-images.githubusercontent.com/79181490/109393045-98e85780-7945-11eb-89f8-5ba2f142ddc0.png)

  
  First time app will show react native page
  
  ![image](https://user-images.githubusercontent.com/79181490/109388806-5f0c5680-792f-11eb-89ea-a1fb5bcaa832.png)
  
  Shake the mobile and it wil show options
  
  ![image](https://user-images.githubusercontent.com/79181490/109388894-d9d57180-792f-11eb-85d5-e6443b4cee68.png)

  
  
  click the debugger and debugger will open in browser automatically
  ![image](https://user-images.githubusercontent.com/79181490/109388881-ca562880-792f-11eb-8489-46f851a1e7d1.png)


 ========================================================================================================================================================================
  
   You can install visual studio  also for react native app
   1. install visual studio from  https://code.visualstudio.com/ link
   2. Install  react library as shown in image
   ![image](https://user-images.githubusercontent.com/79181490/109392624-31310d00-7943-11eb-98f6-5ff7168c9d27.png)
   3. SDK Tools which is already install in android studio otherwise install from https://developer.android.com/studio/releases/sdk-tools
   4. Provide Path in environment variable
   
     **a)** C:\Users\<computerusername>\AppData\Local\Android\Sdk\tools
     **b)** C:\Users\<computerusername>\AppData\Local\Android\Sdk\platform-tools 
     
   5. Instal expo cli

  ![image](https://user-images.githubusercontent.com/79181490/109394740-8888aa80-794e-11eb-80a1-84ac99ae676e.png)


   6.  expo init projectname
    ![image](https://user-images.githubusercontent.com/79181490/109393998-b0760f00-794a-11eb-85ae-2669a0c43087.png)
    
   7. run command in terminal : expo start
   8. It will open browser and dircly click no link where you have to run app

   ![image](https://user-images.githubusercontent.com/79181490/109394629-fe404680-794d-11eb-9585-fcb4a54ee44a.png)`

 
  ![image](https://user-images.githubusercontent.com/79181490/109394754-9a6a4d80-794e-11eb-8d82-458b357b8226.png)


Issue:
  a) if SDK manager error is coming then go to  C:\Users\<computerusername>\AppData\Local\Android\Sdk\tools\bin 
  b) open Command prompt and go to above location 
  c) run command sdkmanager --licenses

