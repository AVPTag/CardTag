# CardTag 
(created by [Hopefullty](https://youtube.com/@hopefullty) on YouTube.)

Jump to: https://github.com/AVPTag/CardTag/blob/main/README.md#requirements

Jump to: https://github.com/AVPTag/CardTag/blob/main/README.md#how-to-update-properly

Jump to: https://github.com/AVPTag/CardTag/blob/main/README.md#how-to-automatically-sign-the-application-every-6-days

Jump to: https://github.com/AVPTag/CardTag/blob/main/README.md#package-information

AVPTag is a way to run Gorilla Tag on a Google Cardboard. Here is how.

1.  Every time a Gorilla Tag Steam VR (PC-VR) update comes out, our app will detect that.
    
2.  When an update is released, your Windows device will be asked to update it on Steam.
    
3.  Your Android/iOS will stream the content over to your Google Cardboard with "splitting" the game in half and making it look like a Google Cardboard app.

4.  Your Android/iOS will receive the "message" from your Windows device and install it

5.  Enjoy CardTag!

# How to set up

Our GitHub repo comes with tools to help you install CardTag super fast. Here is how!

# Requirements

A Windows Device with at least 5 GB free (To install Gorilla Tag) and MUST not be arm windows (only x86_64, 64 bit, or 32 bit, recommended to use 64 bit)

An **optional** macOS device to sideload .ipa

A Mobile Device that has .ipa or .apk support. 

A Google Cardboard -- any type of Google Cardboard. 

# Setup

Windows:

 1. Install git from [https://git-scm.com/downloads/win] or Install in Powershell with ```winget install --id Git.Git -e --source winget```
 2. Run this command: ```mkdir "%USERPROFILE%\AVPTag" && cd "%USERPROFILE%\AVPTag" && git clone https://github.com/AVPTag/CardTag.git```
 3. Install Steam if not already done.
 4. Log in to Steam if not already done.
 5. Purchase Gorilla Tag if not already done
 6. Download & Install Gorilla Tag if not already done.
 7. Install ADB
 8. Continue the rest of the set up below



# How to Update Properly

Windows:

 1. Check Steam before you play Gorilla Tag.
 2. If it says "Update", press the button and install it.
 3. Continue the rest of the update process below.

Mac & Windows:

 1. Make sure AVPTAGCLI is open.
 2. Continue the rest of the update process below.

Mac:

 1. In AVPTAGCLI, type "settings"
 2. A menu will appear. Press right arrow, down arrow, and you should be selected on "Auto Update". Press Enter.
 3. Continue the rest of the update process below.

Windows:

 1. Go to Steam > Library > Gorilla Tag and press the settings icon and press Properties.
 2. Go to the "Updates" tab.
 3. Under automatic updates, press the dropdown.
 4. Press "Immediately download updates"
 5. Continue the rest of the update process below.

Google Cardboard:

 1. Launch AVPTag from the Home View (or Home Screen)
 2. When the menu appears, press "Update Sync Settings"
 3. You will now get automatic updates!


# How to automatically sign the application every 6 days

Mac or Windows:

 1. On one of the two above, open AVPTAGCLI.
 2. Type "settings" and press Enter
 3. You should be selected to AutoSign. Press Enter.
 4. Continue the rest of the signing process below.

Google Cardboard:

 1. Launch AVPTag from the Home View (or Home Screen)
 2. When the menu appears, press "Update Sync Settings"
 3. Press "Open Gorilla Tag"
 4. After you load into Gorilla Tag, you can close the app.
 5. Your AVPTag will now automatically sign itself as long as AVPTAGCLI runs in the background on your Mac (at the least)

# Package Information

Bundle ID: com.hopefullty.avptag

Open Source: false

Age Rating: 13+ to use the Steam version, however this is not enforced as anyone can build our programs.

Category: Gaming

Subcategory: Virtual Reality

Platform: Built for visionOS, but streams from Windows.

License: Proprietary (Personal Project)

Region Availability: Anywhere that does not enforce Steam

Multiplayer/Online Gaming: Yes

Release Status: [==========7%==========]

Half-Finished (https://avptag.github.io/)[AVPTag Website] homepage, Finished README.md, Finished Concept

Next Steps: AVPTAGCLI, Xcode project, Update Website FULLY, Test #1

Potential Next Steps: Bug Fix #1, Test #2 (looped)

Developer Notes: This is a solo, fan-made project — not affiliated with or endorsed by Another Axiom.

Developer Notes continued: Just because it says Potential Next Steps and Tests and no updates on our project does NOT mean that we will not update.

Leaks: We are planning to add "controllers" via mobile, so that you can Launch Gorilla Tag from your mobile device in case you can't launch it regularly. This should work with Android and iOS.

Copyright © Hopefullty Global Records 2025. All Rights Reserved.
