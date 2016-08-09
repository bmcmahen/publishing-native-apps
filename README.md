# publishing-native-apps

## Publishing 

### Android

#### Creating your build
1. https://facebook.github.io/react-native/docs/signed-apk-android.html

### iOS

#### Creating your build 

1. In xCode, select 'Generic iOS Device' as the device target (i.e., where you'd typically select your simulator device).
2. If using react-native, select the menu `Product -> Scheme -> Edit Scheme`. Change `Build Configuration` to `Release`. 
3. If you are updating your app, change the `Version` and `Build` under the `General` tab with your target selected.
4. With your app target selected, select `Build Settings` and search for `Provisioning Profile`. Change `Release` to your distribution provisioning profile.
4. Under the `Product` menu, select `Archive`. Make a coffee. 
5. Select `Upload to App Store`.  Drink your coffee.

The build should appear in iTunes connect within a few minutes (Let's be optimistic).

## Creating Promotional Material

### Android 

#### Generating Icons:

1. In android studio go to: __File > New > Image Assets > select launcher icon > choose image file__
2. It will automatically resize your image. OMG amazing.


### iOS

#### Generating Icons:

#### Generating Preview Screenshots:

Apple requires that you provide screenshots of your app at various sizes to match the corresponding Apple devices. This is a pain in the ass. Guide:

1. Take screenshots of the app in the iPhone 6S Simulator by going to `File -> Save Screen Shot`. These will be saved on your desktop. 
2. Use [AppStoreSketch](https://github.com/MengTo/AppStoreSketch) and Sketch to autogenerate screenshots for the various device sizes.
3. Export, and upload them to iTunes connect.

#### Generating Video:

1. Plug your iPhone into your device, and run your app.
2. Open QuickTime, select `File -> New Movie Recording`. 
3. Turn off the microphone.
4. You should see your iPhone device screen being mirrored in QuickTime, and be able to record the screen.

#### Android
