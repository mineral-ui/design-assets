# Mineral Design Assets

This is a testing ground for distribution of Sketch files, and design metadata.

[![Watch the video](https://raw.githubusercontent.com/mineral-ui/design-assets/master/readme-images/tutorial-coverphoto.gif)](https://www.youtube.com/watch?v=_DQj2wqi09M)

## 1. Prerequisites

### Set files as library
1. After downloading the repo, make sure to open sketch with a new document
2. Go to Sketch > Preferences and click on "Add Library..."
3. Select all the files from the /library/ folder and add them to your symbol library.

### Get the Fonts
1. Go to [Google Fonts](https://fonts.google.com/specimen/Open+Sans?selection.family=Open+Sans:300,300i,400,400i,600,600i,700,700i,800,800i) and download __Open Sans__.
2. Install Open Sans by unzipping the download and double-clicking each font file then clicking "Install" in the preview area.

*Note to Adobe Typekit users: Do __Not__ use the version of Open Sans offered by Typekit. It has a different font ID, and will break the font usage in the Sketch file*

### Install the following sketch plugins
1. [Shared text styles](https://github.com/nilshoenson/shared-text-styles)
2. [Shared sketch palettes](https://github.com/andrewfiorillo/sketch-palettes)

### Importing your theme colors
1. Mineral comes with an array of supported color themes to select for your product. [Check this readme to import your theme colors](https://github.com/mineral-ui/design-assets/tree/master/color-palettes)
2. Once you've imported your theme palettes you may move on to the next section of setup.

## 2. Setting up your theme

*If your application color theme is MineralUI-blue, the following steps are unecessary and you may skip to section 3!"*

1. After you've downloaded the Mineral UI repository and imported your theme palettes, open the "Mineral theme UI settings" sketch file in the Library folder.
2. Open the "🎨 Color" page.

![page list](https://raw.githubusercontent.com/mineral-ui/design-assets/master/readme-images/pages.png)

3. Where prompted to replace the color swatches with your theme colors you may replace each color with the theme you selected in the previous section.
    * You may use your imported palette to quickly replace the 10 colors on this page.

![Pallete list](https://raw.githubusercontent.com/mineral-ui/design-assets/master/readme-images/10-palettes.png)

4. After you've replaced these ten colors, view the "✏️ Text styles" page.
5. In the right column of text, replace the color for each of text layer with the color base **60** of your theme. (do each individually)

![text layers](https://raw.githubusercontent.com/mineral-ui/design-assets/master/readme-images/theme-text-styles.png)

6. As you update each of these layers don't forget to sync the text styles.

![text layer sync](https://raw.githubusercontent.com/mineral-ui/design-assets/master/readme-images/sync-text.png)

7. After you've updated all three of your text styles and synced them, go to Plugins > Shared Text Styles > Export text styles

![Export text styles](https://raw.githubusercontent.com/mineral-ui/design-assets/master/readme-images/export-text-styles.png)

5. Save the export file with name a name of your choice
6. Save and close this sketch file.

### Icons

1. Now open the "Mineral UI icons" sketch file, in the top right corner it should have a button stating "Updates available."

![Library updates available](https://raw.githubusercontent.com/mineral-ui/design-assets/master/readme-images/updates-available.png)

2. Click this button and click update on the verification window.
3. Now all of your icons should be matching your theme color.
4. You may now save and close this file.

### Mineral UI utilities & Others

1. Open up the "Mineral UI utilities" sketch file.
2. Go to Plugins > Shared Text styles > Import text styles and select the file you exported earlier
3. Text styles on various symbols should now be updated.
3. In this file you will also see "Updates available," similar the last steps press this button and go ahead and update all symbols and styles.
4. Save and close this file
5. Open all other files under the library folder and repeat steps 1-4.

Now you may create your own file and start using these files as a library.

**Note: Any symbols under "partial" is for construction purposes only. Symbols to build UI will not be located in these menus.**

## 3. Updating repository

### Updating your library

1. Commit any changes you have made to your library using the command `git commit -a -m "notes here"` Where you can put any notes you would like.
2. use command `git pull -X theirs` this way it will auto merge any conflicts with the latest master. If you don't do this merge conflicts may arise that are unfixable.


### Troubleshooting

If you do end up with merge conflicts, the best option to fix is using command `git reset --hard` and afterwards doing `git pull -X theirs` to get the latest libraries.

If your library isn't matching your selected theme after an update - you may need to update the theme library files again. (*Note, updating will not break symbol links in your design files*)

Music in videos by: www.bensound.com
