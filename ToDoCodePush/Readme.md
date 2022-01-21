How to Install and Use this Application on Mac using React Native CLI:

1. If not already installed, install Homebrew:

    /usr/bin/ruby -e “$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

2. If not installed, install Node.js:

    brew install node

3. Install Watchmen:

    brew install watchman

4. Install React-Native CLI:

    npm install -g react-native-cli

5. Install XCode:

6. Install Xcode Command Line Tools:

    Open Xcode -> Preferences -> Locations tab -> install the latest version of Xcode command line tools.

6. Go into the root of the downloaded project folder and install package dependencies:

    npm install

7. Still in the root of the project folder, install the pods (package dependencies) for the mac section of the project:

    npx pod-install ios

8. In the root of the project folder, navigate to the ios folder and open the file named ToDoCodePush.xcworkspace in XCode. Go to the 'Signing and Capabilities' menu for the project. Select your Team for the project. In order to add a team, you have to sign in with your apple account in XCode preferences.

9. In the terminal, go back to the root of the project folder and run the project by typing in the terminal:

    react-native run-ios

9. Another way to run the project is to go into the IOS folder in the root of the project and open the file named:

    ToDoCodePush.xcworkspace

10. Make sure to open the .xcworkspace file NOT the .xcodeproj file. Otherwise the project will not be able to load the pod file dependencies and building the project will fail.

