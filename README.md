# Setting up macos dev machine

## install Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Install Node using nvm
```
brew install nvm
source $(brew --prefix nvm)/nvm.sh
nvm install node
```

## Install vscode
download and install from 
https://code.visualstudio.com/download

## Install xcode
Find xcode in the App Store

## Install java sdk
download the latest Java JDK from 
https://www.oracle.com/java/technologies/downloads/#jdk21-mac

## Install Android Studio
Download from https://developer.android.com/studio


## Install Cocoapods
```
brew install cocoapods
brew link cocoapods
```

## Install gradle
```
brew install gradle
```

## Install Ionic CLI
```
npm -g @ionic/cli
```

## Install VSCode ionic extension
in vscode search for the 'ionic' extension
```
Name: Ionic
Id: Ionic.ionic
Description: Official extension for Ionic and Capacitor development
Publisher: Ionic
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=ionic.ionic
```

## Install the VSCode Excalidraw extension
In VSCode search for the 'excalidraw' extension
```
Name: Excalidraw
Id: pomdtr.excalidraw-editor
Description: Draw schemas in VS Code using Excalidraw
Version: 3.7.3
Publisher: pomdtr
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=pomdtr.excalidraw-editor
```


## Now onto some dev stuff
You can create a new ionic project using the vscode extension, or cli, after you have created the template though, it is recommended to open the project in Android Studio for it to complete the configuration of the JDK and Android dependencies.

Now, build something cool.
