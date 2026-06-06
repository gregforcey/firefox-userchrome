# Custom Firefox `userchrome.css` file

The current configuration performs the following:
* Reduces all the bookmarks bar items to icons 
* Centers the bookmark icons and folders on the toolbar
* Shows folder names for any folders stored in the bookmarks bar

You can also optionally compact the icons and folders in the bookmarks bar by uncommenting one of the css snippets. 

# How to install
1. Type `about:config` in the Firefox URL bar and press `Return`.
2. Accept the risk if you get a warning about changing settings in `about:config`. 
3. Search for the option `toolkit.legacyUserProfileCustomizations.stylesheets` and change the setting to `True`.
4. Determine Firefox profile folder by going to `about:profiles` and open the root directory folder for the profile you want to change the bookmark bar settings. See [this link](https://support.mozilla.org/en-US/kb/profiles-where-firefox-stores-user-data) for more information on how to locate your Firefox profile folder. 
5. Quit Firefox
6. Copy the `chrome` folder with the `userchrome.css` file to your Firefox Profile folder.
7. Launch Firefox
