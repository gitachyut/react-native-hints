### For Horizontal ScrollView   
`<ScrollView  horizontal ></ScrollView> `    
### Horizontal ScrollView Without Indicator  
`<ScrollView  horizontal showsHorizontalScrollIndicator={false}>`   

### Remove android default TextInput underline   
`< TextInput underlineColorAndroid='transparent'  />`  

#### Some Commands   
`cd ~/Library/Android/sdk/emulator/`  
`emulator -avd my_avd`  
`emulator -avd my_avd  -wipe-data`  
`emulator -list-avd`  

##### For Building  
`react-native bundle --dev false --platform android --entry-file index.js --bundle-output ./android/app/build/intermediates/assets/debug/index.android.bundle --assets-dest ./android/app/build/intermediates/res/merged/debug`    

`cd android`  
`./gradlew assembleDebug`  

### Status Bar . 
`    <StatusBar
      translucent
      backgroundColor="rgba(0, 0, 0, 0.20)"
      animated
    />`


