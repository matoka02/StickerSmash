# About this tutorial
The objective of this tutorial is to get started with Expo and become familiar with the Expo SDK. It'll cover the following topics:

## Create an Expo App
**01.** Break down the app layout and implement it with flexbox.  
**02.** Use each platform's system UI to select an image from the media library.  
**03.** Create a sticker modal using the `<Modal>` and `<FlatList>` components from React Native.  
**07.** Add touch gestures to interact with a sticker.  
**05.** Use third-party libraries to capture a screenshot and save it to the disk.  
**06.** Handle platform differences between Android, iOS, and web.  
**07.** Finally, go through the process of configuring a status bar, a splash screen, and an icon to complete the app.  

## Run the app on mobile and web  
Installing dependencies: 
```
npm install
```
In the project directory, run the following command to start a development server from the terminal:
```
npx expo start
```
Once the development server is running, the easiest way to launch the app is on a physical device with Expo Go. For more information, see [Open app on a device](https://docs.expo.dev/get-started/start-developing/#open-the-app-on-your-device).

To see the web app in action, press w in the terminal. It will open the web app in the default web browser.

Once it is running on all platforms, the project should look like this:

[app-running-on-all-platforms](https://docs.expo.dev/static/images/tutorial/01-app-running-on-all-platforms.jpg)

App running on all platforms
The text displayed on the app's screen above can be found in the **App.js** file which is at the root of the project's directory. It is the entry point of the project and is executed when the development server starts.
