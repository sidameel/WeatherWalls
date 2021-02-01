# WeatherWalls

WeatherWalls is an iOS Shortcut created by /u/apoch8000. The shortcut takes the current weather conditions on your location and sets an according wallpaper on your device.

**Table of contents**
* [Features](#features)
* [Requirements](#requirements)
* [Setup](#setup)
* [Automate](#automate)
* [Tips & Tricks](#tips--tricks)
* [FAQ](#faq)

## Features
WeatherWalls has several (optional) features to give you and your device a nice experience. Find a list of the features below.
- **Up to 9 different weather conditions** can be shown: Clear, Minor Clouds, Cloudy, Heavy Clouds, Drizzle*, Rain, Fog, Snow and Thunderstorm*. (* Only available in select themes)
- **4 Themes to choose from** ('Sea', 'Beach', 'Mountain' & 'Surface'). 
- Each theme has its own **Day / Night** version.
- The 'Sea' and 'Beach' themes have a **Sunrise / Sunset** effect.
- **Easy installation** with a seperate installer shortcut. 

**If you follow this guide precisely, WeatherWalls will work like a charm on your device.**

## Requirements

**Allow 'Untrusted Shortcuts'** on your device by going to **Settings → Shortcuts**.

The shortcut is only working on **iPhone** models running **iOS 14.3** or **higher** as the '*Set Wallpaper*' action was (re)introduced in this version.

## Setup

Before WeatherWalls can work, we need to make sure all images are in the correct folders. You can either choose to run the **installer shortcut** or **manually** download and extract all files to the correct locations.

### Get the files ###
On your iPhone, click on the link below for the installer shortcut. Run it to download and extract all files. Once completed, you can delete the installer shortcut again.
* **[Installer](https://www.icloud.com/shortcuts/e2a95aa7465f4a118a62befbbde1c81e)** (For version 2.4 or above) - *01 Feb. 2021*

The easiest way is to install all required files with this installer. It downloads the themes you want and extract them to your iCloud Drive.


#### Manual setup ####
Despite this is not recommended, you can choose to manually download the files and extract them to the right locations. Follow the steps below:
1. In your **iCloud Drive**, find the `/Shortcuts` folder.
2. In this directory **create a new folder** named `WeatherWalls' (= `/Shortcuts/WeatherWalls`). 
3. In this directory **create a folder for the theme** you want to download and **capitalize the name** (= `/Shortcuts/WeatherWalls/BEACH`).
4. **Download** the theme from above with the according foldername you just created.
5. **Extract** the contents of the theme into your theme folder (= `/Shortcuts/WeatherWalls/BEACH/clear.jpg`).

You have now manually installed a theme.

## Get the shortcut
Click on the link below to install the most recent version of WeatherWalls
* **[Version 2.4](https://www.icloud.com/shortcuts/3e4b5b8d871c43fc80ea671ee5fe4836)** - *01 Feb. 2021*

Changelog coming soon.

## Automate

**WeatherWalls does not update your wallpaper automatically by default**. You can either choose to **manually trigger this shortcut** every time you want your wallpaper to update **OR** you can choose to **use automations** to trigger the shortcut.

[Create your own automations to your preferences](https://support.apple.com/guide/shortcuts/create-a-new-personal-automation-apdfbdbd7123/ios) and add a 'Run Shortcut' action. Choose the WeatherWalls Shortcut to run and you're set.

Recommended is to run WeatherWalls approximately every 1-2 hours and maybe more frequent around the sunrise/sunset period to fully enjoy the effect. Alternatively you can choose to run the shortcut every time you open/close one of your most used apps (also through Automations) to make sure your wallpaper is updated from time to time. 

**IMPORTANT NOTE** 
Running this shortcut too frequently through some automations (e.g. Every time I open app, run shortcut) can have a negative impact on the battery life of your device. It is suggested to use the feature to limit the shortcut to only run once every 10-15 minutes at least. 

## Tips & Tricks

**Disabling Automations notifications**

Using automations throughout the day will flood your notifications as Shortcuts notifies you every time an automation runs in the background. There is no way to turn off notifications for Shortcuts in Settings → Notifications, though there is a glitch that makes it possible to turn off those notifications.

Go to Settings → Screen Time → All Activity. Scroll down to the Notifications section. You'll see different apps you used in the past day with a clickable arrow. Shortcuts will be there too, but probably won't have an arrow (yet). Scroll through the chart horizontally a few times back and forth, until a clickable arrow comes available on Shortcuts. Click it and you should be prompted with a Notifications settings page for Shortcuts. If you disable notifications here, Shortcuts automations will still run in the background, but you will no longer be notified. Note that this glitch resets when you restart your device.

## FAQ

- **I get an error where '*there is no key provided*' when I run the shortcut?**

**This is a known bug that I cannot solve.** This shortcut uses Microsoft Translate service to translate the weather conditions from your default device language to English to find the matching image. Some conditions are somehow not translatable (e.g. 'Halbbewölkt' in German doesn't translate to 'Partly Cloud' thus won't show the correct condition). 
The only way to fix this is by manually adding the condition in the vocabulary list in the shortcut and assign the matching wallpaper.

- **The wallpapers seem to be pixelated / low quality?**

Depending on your device, the shortcut needs to resize the original images to fit your screen and uses overlay actions to create e.g. the sunrise/sunset effect. In this process, the quality of the images seems to be reduced, causing blurry or pixelated results in some cases. There is nothing I can do to solve this.

- **Will you make an iPad version?**

**Not in the near future.** An iPad version would need their own set of images, which currently does not exist as the shortcut initially was designed for an iPhone. There are no plans to make the shortcut compatible for iPad.

- **Will you make more variations?**

**Probably.** Depending on my personal life and spare time, there probably will come more variations over time.

- **Is this shortcut 'battery hungry'?**

**No.** Only your automations will define how much resources will be used. If you e.g. run the shortcut every 10 minutes, there will be a noticeable effect on your battery life. I tested the shortcut (version 2.0) and let it run 50 times throughout the day. My battery stats told me it used 2% as background activity on a day of moderate usage (iPhone 11 / 88% battery life).

- **Can I get your source files to the wallpapers?**

**No**. I am not sharing my source files with anyone. I created them manually in Photoshop and took the original images from Unsplash (except the original Microsoft Surface wallpaper). Anyone can create its own set of wallpapers, place them in a manually created folder and name the images accordingly.

- **Do you accept paid assignments to create a custom variations?**

**Everything is negotiable** but it is not my intention to start creating private variations for the highest bidder. If people buy me a coffee from time to time, I probably stay motivated to add new variations from time to time, that everyone can enjoy.

- **Do you want a coffee?**

**I thought you'd never ask!** Yes, you can buy me a coffee via [paypal.me/WeatherWalls](http://paypal.me/WeatherWalls).


