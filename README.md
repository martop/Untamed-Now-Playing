[Untamed Now Playing](https://github.com/untamed0/Untamed-Now-Playing) v0.3-dev
=================
"Untamed Now Playing" is a Chrome extension which parses the song title and artist from popular online radio/music sites, and writes it to a file on your hard drive. Programs such as Xsplit can then read the file and display it on an overlay, allowing viewers to easily see what song is currently being played. At the moment, this extension is Windows only.

Supported Sites
--------------------------------------
* [ah.fm](http://ah.fm)
* [di.fm](http://di.fm)
* [grooveshark.com](http://grooveshark.com)
* [pandora.com](http://pandora.com)
* [soundcloud.com](http://soundcloud.com)
* [youtube.com](http://youtube.com)

Support for more sites will be added over time. If you have a suggestion for a site, please open an issue or reply to the teamliquid topic.

Install
--------------------------------------
There are a couple of ways to install the extension;

### Install the packed extension
1. Download the already packed extension [here](http://ipaddr.me/unp/download.php)
2. Open Chrome, click on the Spanner/Wrench icon -> Tools -> Extensions.
3. Drag and drop the packed extension you downloaded in Step #1.
4. Click 'continue' on the bottom left of the Chrome window.

### Install the unpacked extension
1. Download the extension from Github [here](https://github.com/untamed0/Untamed-Now-Playing/zipball/master)
2. Extract the files to a safe place.
3. Open Chrome, click on the Spanner/Wrench icon -> Tools -> Extensions.
4. Tick "Developer mode" on the top right of the page.
5. Click "Load unpacked extension" and navigate to where you extracted the files in Step #2.

Note, the unpacked extension may have later additions to the code, as the plugin is in development. Also, you can ignore any warning about the manifest being outdated, this will be fixed in a later version.

Configuration
--------------------------------------
Once you have installed the extension, you can find the options page by either right clicking the music note icon next to the address bar and selecting Options, or by finding "Untamed Now Playing" on the Extensions page and clicking Options.

The main option to configure is the "Save Directory". This is where the file containing the now playing data will be saved. The directory will also be used for caching if you enable the "Check stream is live" option. More information explaining each option can be found by clicking the info button on the right of each option.

Limitations
--------------------------------------
At the moment, now playing data is only saved when the song intially plays and is only updated when the next song starts playing. Thus if you stop playing music, the output file will still contain the last song played.

Chrome limits what directories can be saved to, if you run into problems, try saving to a subdirectory of your profile (C:\Users\USERNAME\* or C:\Documents and Settings\USERNAME\*).

Licence
--------------------------------------
This software is provided "AS IS" without warranty of any kind, either expressed or implied. Licensed under a [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/deed).

This software uses the following libraries developed by third parties, and are licenced seperately;
* [Bootstrap](http://twitter.github.com/bootstrap) (Apache License v2.0)
* [jQuery](http://jquery.com) (MIT License)
* [npapi-file-io](http://code.google.com/p/npapi-file-io) (New BSD License)
* [Sammy.js](http://sammyjs.org) (MIT License)

Additionally, the main icon was designed by [CSS Creme](http://csscreme.com/freeicons/).