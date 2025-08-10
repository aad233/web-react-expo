## 🚀 Previewing the App

**You can preview the app using one of these methods:**

### 1. Using Expo Go (Recommended)
1. **Install [Expo Go](https://expo.dev/go) on your mobile device** (iOS or Android).
2. **Clone this repository:**
   ```bash
   git clone https://github.com/aad233/web-react-expo.git
   cd web-react-expo
   ```
3. **Install dependencies:**
   ```bash
   npm install
   ```
4. **Start the development server:**
   ```bash
   npm start
   ```
   or
   ```bash
   expo start
   ```
5. **Scan the QR code** shown in your terminal or browser with the Expo Go app to open the live preview on your device.

### 2. Web Preview
- After starting the server, open [http://localhost:19006](http://localhost:19006) in your browser to see the web version.

### 3. Hosted Preview
- If a hosted preview (Expo Snack, Vercel, Netlify) is available, the link will appear here:
  ```
  [Live Preview](YOUR_PREVIEW_LINK_HERE)
  ```

---

**Troubleshooting:**  
If you encounter issues, ensure you have Node.js and npm installed, and your device is on the same Wi-Fi network as your development machine.

---

*Feel free to update this section with specific preview links or instructions as your deployment setup evolves!*

> Edited for use in IDX on 07/09/12

# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

#### Android

Android previews are defined as a `workspace.onStart` hook and started as a vscode task when the workspace is opened/started.

Note, if you can't find the task, either:
- Rebuild the environment (using command palette: `IDX: Rebuild Environment`), or
- Run `npm run android -- --tunnel` command manually run android and see the output in your terminal. The device should pick up this new command and switch to start displaying the output from it.

In the output of this command/task, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You'll also find options to open the app's developer menu, reload the app, and more.

#### Web

Web previews will be started and managred automatically. Use the toolbar to manually refresh.

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.