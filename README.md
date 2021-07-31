# RFMG-WonderCMS-Theme-Developmental
RFMG WonderCMS Theme - Developmental Version

## Features
1. Responsive Design
2. Contact Form Plugin Pre-Integrated (Just uncomment the specified code in theme.php after installing the plugin.)
3. Responsive YouTube Video Embedding

## How to use
1. Login to your WonderCMS website.
2. Click "Settings" then click "Themes".
3. Scroll all the way to the bottom and add "https://github.com/FanboyStudios/RFMG-WonderCMS-Theme-Developmental" to your custom repository.
4. If it added the theme successfully to your custom repositories, you can go back to "Themes" the click "Install".
5. If the theme installed successfully you can go back to "Themes" and select the theme to activate it.

## Updates
1. Login to your WonderCMS website.
2. Click "Settings" then click "Themes".
3. Click "Check For Updates".
4. If there's any updates, there will be a button to update the theme for you to click.
5. Click the update button and the theme will be updated... and automatically applied if the theme is set.
6. Edit Contact Form as needed if you are using the Contact Form Plugin.

## How To Use Responsive YouTube Embeds
1. Copy the code from the code block... or from the theme description!
2. Paste it into the editor. (If you are using the Summernote Plugin, use "Code View" mode.)
3. Edit the embed identifier to your identifier from your video. This is found at the end of a YouTube Video URL.
(Example https://www.youtube.com/watch?v=knl_V735US4 becomes https://www.youtube.com/embed/knl_V735US4) *This video is my channel trailer. :) Check out my channel sometime!*

Code:
```
<div class="video-container">
  <iframe src="https://www.youtube.com/embed/knl_V735US4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
```

### How to fix your site if it breaks due to your modifications to this theme. (At least most of the time.)
0. YOU WILL LOSE SITE DATA, WHICH MAY INCLUDE YOUR POSTS, PICTURES, AND OTHER IMPORTANT FILES. MAKE A BACKUP!
1. Delete the "cache.json" and "database.js" files from your WonderCMS "data" folder.
2. Delete the folder for this theme in the WonderCMS "themes" folder. Don't delete the whole "themes" folder itself though.
3. Refresh your webpage.

## Preview
![Theme preview](/preview.jpg)
