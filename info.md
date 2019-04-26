# to-Do App w/ React Native

following tutorial: 
https://pusher.com/tutorials/build-to-do-app-react-native-expo


full code: 
https://github.com/amandeepmittal/rn-todos-example


1. Setup
    - expo init rn "To Do" s-example
    - minimal template

2. Start
    - expo-cli start

3. Folder Structure
    - app dir with utils & components dir and also Main.js
    - create Colors.js in utils

4. Coding

    1. change app.js with Main Component
    2. create Main.js
        - linearGradien Component wrapping around View (from 'expo')
    3. Header.js
        - Text Component with dynamic title (const declared in App.js and passed as Props)
    4. Input Component
        -TextInput (different Props like autoCorrect, value, etc.)
        -add Input Comp to Main.js and create callback functions, and add state of value to Main Comp
    5. List Component
        - using Platform to detect device
        - Dimensions.get() to get width and height of device
        - MaterialIcons from @expo/
    6. in Main.js add List with ScrollView

    missing Button and Subtitle Component -> add those to Main.js
    