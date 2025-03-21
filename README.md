
## ℹ️ Introduction

Real Time Chat Application that written in [React Native](https://reactnative.dev/) and [Expo](https://expo.dev/) platform.
It uses [Firebase](https://firebase.google.com/) (Web version 9) realtime database.  

- For the live demo video see [Demo.mp4](./media/ReactNativeChat-Live-Demo.mp4)     

https://github.com/Ctere1/react-native-chat/assets/62745858/bcde4aa0-d2f2-4d8c-8716-bf274c059d2e

>[!Note] 
  You can check the screenshots below

 
## ⚡Features
 
| Feature             | Description                                                                                           |
| :------------------ | :---------------------------------------------------------------------------------------------------- |
| `Signup and Login`  | Firebase Email/Password sign-in method. Allow users to sign up using their email address and password |
| `Send Text Message` | Essential for casual messaging                                                                        |
| `Send Picture`      | You can send pictures without losing quality                                                          |
| `Group Chat`        | You can send your messages to multiple people at the same time                                        |
| `Delete Chat`       | You can delete chats after holding and selecting them                                                 |
| `Delete Account`    | You can delete your account                                                                           |
| `Real Time Chat`    | The last incoming message will be placed at the top of the chat screen                                |
| `Users List`        | Registered users sorted by alphabetical index (A -> Z)                                                |
| `Note to Self`      | You can also take notes by sending a message to yourself                                              |

## 💾Installation Guide
 
 To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com))    installed on your computer. 
 
 ```bash
 # Clone this repository
 $ git clone https://github.com/Ctere1/react-native-chat
 # Go into the repository
 $ cd react-native-chat
 # Install dependencies
 $ npm install
 ```

 > For running the app:
 ```bash
 # Go into the repository
 $ cd react-native-chat
 # Run the expo
 $ npx expo start
 ```
 
 After these steps install the [Expo Go](https://expo.dev/go) mobile app from the Google Play Store or Apple App Store on your testing device. This app allows you to run and test React Native applications built with Expo.
 
 > [!Warning]  
   Do not forget to setup `.env` file for Firebase connection. Please see the [doc](https://firebase.google.com/docs/firestore/quickstart) or see this [comment](https://github.com/Ctere1/react-native-chat/issues/1#issuecomment-2414810841)

