
# iOS Swift Chat App

<div>
<img align="left" src="https://github.com/cometchat-pro-samples/ios-swift-chat-app/blob/v2/Screenshots/appScreenshot.jpg">  </div>

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed the latest version of Xcode. (Above Xcode 12 Recommended)

- iOS Swift Chat App works for the iOS devices from iOS 11 and above.

NOTE: Please install the latest pod version on your Mac to avoid integration issues

```bash
Please follow the below steps:

sudo gem update cocoapods --pre
pod update
clean
build

```
___

## Installing iOS Swift Chat App
      
1. Simply clone the project **ios-chat-ui-kit-app** repository from github. After cloning the repository:

2. Navigate to project's folder and use below command to install the require dependancies.
   
   ```
   $ pod install
   ```

3. If you're facing any issues while installing pods, then kindly use the below command to install dependancies.
   
    ```
   pod install --repo-update
   ```

4. Build and run the Sample App.
___

## Running the sample app

To Run to sample app you have to do the following changes by Adding **AppID**, **AuthKey** and  **Region**.
   
   You can obtain your  *App ID*, *Auth Key* and *Region* from geekwork
          
   - Open the project in Xcode. 
          
   - Go to CometChatSwift -->  **AppConstants.swift**.
                  
   - Modify *App ID* and *Auth Key*  and *Region* with your own **App ID**, **Auth Key** and **Region**.

   -  Select demo users or enter the **UID** at the time of login once the app is launched. 

![Studio Guide](https://github.com/cometchat-pro-samples/ios-swift-chat-app/blob/v2/Screenshots/Auth.png)    

---

## Add UI Kit to your project

Learn more about how to integrate [UI Kit](https://github.com/cometchat-pro/ios-chat-uikit) inside your app. 
