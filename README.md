# Iconsur GUI:
## "IconSur: macOS Big Sur Adaptive Icon Generator
npm version npm downloads github commits
iconsur is a command line tool to easily generate macOS Big Sur styled adaptive icons for third-party apps.

The generation is based on the most related iOS app from the App Store, or, if there isn't one, is created from the original icon, in which case the background color and the scaling can be customized." (https://github.com/rikumi/iconsur)

### IconsurGUI turns the command line tool into a simple applescript applet that adds a usable interface to Rikumi's iconsur.


FAQ:

------------------------------------------------------------------

Q) Why do I need another iconsur-named file in my downloads to run IconsurGUI?

A) IconsurGUI works by resizing

------------------------------------------------------------------

Q) Why do I need to keep the system preferences window open when I use Mimic8D?

A) Since the slider for balancing lives in system preferences, closing the window, or even switching to fullscreen in an app, essentially hides the app from view. All you have to do is keep the sound pane of system preferences open in the background.

------------------------------------------------------------------

Q) It doesn't let me open the installer because it's from an unkown developer. What does that mean and what should I do?

A) If you try to open an app that isn't registered with Apple by an identified developer, you get a warning dialog, and your mac won't let you open the app. While it's true I could have put malicious code into these apps, you can look at the code yourself before running Mimic8D, or StopMimic by opening them in automator.
###### To bypass this, either control+click (right click) either app and select "open" from the popout menu. Another way is to open system preferences, go to "Security and Privacy" and press "Open anyway."

------------------------------------------------------------------

Q) How do I get rid of the System Preferences prompt that appears every time I launch Mimic8D?

A) To do this, you will need to open Mimic8D in Automator. (Automator>Open Existing Document>Mimic8D) Once you have Mimic 8D opened, delete all code starting from **"## Delete from here until it says "STOP HERE" to get rid of the prompt about system preferences."** up until **"## STOP HERE ## STOP HERE ##"**

------------------------------------------------------------------

Q) Why does it sometimes randomly stop?

A) This has happened to me before, only when running the script from Automator directly. I had to constantly click the application icon to get it to resume. 
###### Don't run Mimic8D directly from Automator...

------------------------------------------------------------------

# Modes:

Currently, upon opening Mimic8D, there will be different options that you can choose from. 

![alt text](https://github.com/salameanon/Mimic-8D/blob/main/resources/ExampleModes.png?raw=true)

###### Each provides a different listening experience with the exception of the Help and Stop options.

Fake8D - Moves audio left and right slowly, and works best with headphones.

Jump - This option moves audio left and right much faster, (given the name jump) and in my opinion works best with internal/external stereo speakers.

Skip - I'm not sure why this is an option, although it's here... All it does is switch between Left/Right extremly fast. It almost feels like you are listening to the radio in a car with a window open as it makes the shaking voice sound...

"---" - They don't do anything. They are just seperators.

Help - Directs you to this readme.md. Mmight add a built in FAQ later on.

"---" - Another seperator

Stop - Provides a download link to StopMimic if you deleted it. Also provides the menu bar method of stopping Mimic8D

---MORE COMING SOON???---
