npm install -g expo-cli
npx create-expo-app nameofproject --template
cd nameofproject
npx expo install react-dom react-native-web
npm install --save-dev @types/react @types/react-native
npm install firebase
npm install -g firebase-tools
npx expo install @react-native-async-storage/async-storage

// Copy the code to App.tsx from here: https://pastebin.com/LTCdR0JX
// Now do the firebase wala stuff

npm start
// press "w"
