# IconSurGUI

## Incorporates the Command Line Tool "IconSur" into a simple applescript applet which adds a usable interface to Rikumi's IconSur. (You press a button, it handles the command for you)

#### (https://github.com/rikumi/iconsur)

##### Please let me know if you would like me to take this down or credit you in any other ways.

<span align="center">

---

### Original Description: (https://github.com/rikumi/iconsur/blob/master/README.md)

---

# IconSur: macOS Big Sur Adaptive Icon Generator

<a href="https://www.npmjs.com/package/iconsur"><img title="npm version" src="https://badgen.net/npm/v/iconsur" ></a>
<a href="https://www.npmjs.com/package/iconsur"><img title="npm downloads" src="https://badgen.net/npm/dt/iconsur" ></a>
<a href="https://github.com/rikumi/iconsur/commit"><img title="github commits" src="https://badgen.net/github/last-commit/rikumi/iconsur" ></a>

</p>

</span>

#### `iconsur` is a command line tool to easily generate macOS Big Sur styled adaptive icons for third-party apps.

The generation is based on the most related iOS app from the App Store, or, if there isn't one, is created from the original icon, in which case the background color and the scaling can be customized.

![image](https://user-images.githubusercontent.com/5051300/85926574-ebfb9d80-b8d2-11ea-836b-28e38d1f3447.png)

---

# TUTORIAL:

---

### 1. Download and install the latest release of IconSurGUI from here: https://github.com/salameanon/IconSurGUI/releases

###### Make sure you either Control+Click (Right click) the package and press "Open" to bypass the unknown developer message. Alternatively, you can open Settings, go to Security and Privacy, and press "Open Anyway." Do **NOT** move IconSurGUI to the trash.

### 2. Run IconSurGUI and choose from one of the options - simple as that!

###### For more info on what the options do, scroll down to the *Modes* section of this readme.

---

# MODES:

---

#### Custom Image 📁 
##### Allows you to choose a custom image to be resized and fitted to BigSur's app shape, and then applied to your app of choice.

---

#### iOS AppStore Icon Downloader 🛍
##### Allows you to search the iOS AppStore for an icon matching your app choice's name. If no (relevant) results are found, your app will be resized with a white boarder surrounding it.
###### For example, if I choose "Zoom" as my app choice, IconSur will look through the iOS's AppStore for an app called "Zoom" and then apply its icon to the "Zoom" app on my Mac.

---

#### Resize Current App Icon 🤏
##### Takes the chosen app and resizes it with a white border to fit BigSur's icon shape. 
###### Custom colors probably coming soon unless I forget about this project...

---

#### Modify a System App Copy 📝
##### Since you can't modify System Apps due to the root volume being Read-Only, this feature allows you to make a copy of the System app and modify the icon.
###### For example, if you choose "AppStore" and try to change it's icon, this option will make a COPY of it and modify its icon since you can't modify system icons. From there you can proceed to drag that icon to your dock, launchpad, etc. This is also useful if you don't have administrator permissions on your user account and want to have custom icons.

---

#### Extract App Icon 🔍
##### (NOT MADE BY ME) Asks the user (you) to select an app, them extracts any icon files (.icns) and copies them into a folder created on the Desktop.
###### If there are multiple .icns files, you will be prompted to choose which ones you want to extract. Additionally you can convert the .icns file to the .png format.

---

#### Refresh Icon Cache 🌀
##### Reloads Dock & Finder to forcefully update new app icons
###### This happens automatically after every modification to an app icon made using IconSurGUI

---

#### Reset App Icon 🔙
##### Removes any custom icon the selected app has and replaces it with the .icns file inside of it's resources folder

---

#### Help ❓
##### Brings you to this README.md file
###### A possible built in FAQ section might come in a future version...

---

#### Download BigSur Icons ⬇️
##### Redirects to a HUGE collection of community made BigSur icons at https://macosicons.com/
###### THIS ISN'T MADE BY ME!!

---

#### Delete IconSur 🚫
##### A built in option to remove IconSurGUI
###### This won't affect any custom icons on your apps.

---

#### Submit Feedback 📩
##### Directs you to issue report templates where you can submit feedback, report a bug, request a feature, etc.
###### You need a GitHub account to access these templates and submit feedback.

---

# FAQ:

---

Q) Why does it say I can't open the app because it's from an unknown developer?

A) You need to control+click (right click) the downloaded package and select "open" to bypass GateKeeper. Additionally, you can open the Security and Privacy pane of System Preferences and press "Open Anyway"

---

Q) Why does it say I need to download the "IconSur Binary?"

A) You are using an older version of IconSurGUI or you modified IconSurGUI's resources folder. (Re)Download the latest release here: https://github.com/salameanon/IconSurGUI/releases

---
