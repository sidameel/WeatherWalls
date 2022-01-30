# Creating your own theme or module

## Module

### Folder (If needed)

Create a subfolder in your `/Shortcuts/WeatherWalls/Modules/`folder. The folder name should describe the kind of module you are making. Then create another folder inside it with the name of the module `/Shortcuts/WeatherWalls/Modules/Category`. Remember, that your module installer shortcut/ your module shortcut should automatically create these folders. 

### Shortcut

Now create a shortcut, which applies your theme to the shortcut input and make shure, that the output is the picture of the wallpaper.


## Theme

### Folder

Create a subfolder in your `/Shortcuts/WeatherWalls/Themes/`folder. The folder name must be **capitalized and one word**. Let's use the name `Customtheme`as name for your theme as example. So, you should have `/Shortcuts/WeatherWalls/Themes/CUSTOMTHEME`now.

### Files

At this moment (Version 3.0/Version 4.0 Beta) every theme comes with 19 image files (18 for weather conditions and 1 for sunrise/sunset effect) and in case you want to submit your theme to the WeatherWalls project, your theme should too. It is required that your images are **at least 1284x2278 pixels at 300ppi**.  

Naming the images are important and these should be included in your theme:

**Daytime**
* clear.jpg
* cloud_small.jpg
* cloud_medium.jpg
* cloud_big.jpg
* drizzle.jpg
* rain.jpg
* fog.jpg
* thunderstorm.jpg
* snow.jpg

**Nighttime**
* clear_night.jpg
* cloud_small_night.jpg
* cloud_medium_night.jpg
* cloud_big_night.jpg
* drizzle_night.jpg
* rain_night.jpg
* fog_night.jpg
* thunderstorm_night.jpg
* snow_night.jpg

**SUNRISE/SUNSET**
You can add this effect by using a PNG-file that is used in the overlay action in the shortcut. Creating a realistic sunrise/sunset effect with a single image is challenging. If you don't want the effect, create a 100% transparent PNG-file with the same dimensions as the other images. Name this file **sunset.png** and include it.

Eventually you should end with 18 JPG files and 1 PNG file in `/Shortcuts/WeatherWalls/Themes/CUSTOMTHEME`.

## Submit your theme or Module
If you want to submit your theme to be available in the installer so everyone can download, follow the steps below.
1. Compress the 19 image files in a **.zip file**. Make sure you don't compress the folder with the images within, but only the images directly in the archive. **Make sure the archive is not bigger than 25MB due restrictions on Github**. Optionally you can include a readme file.
2. Upload the archive to a service and send me a link to me at [/u/Firefox6_66](https://www.reddit.com/user/firefox6_66).
3. I will review your submission (correct filenames ect.) and add your theme to the `themelist.json` so everyone can download it.
