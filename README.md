Clarify Video Player
======================

This is a video player extension for the jplayer.org video player. It provides any easy way to show Clarify search results in the scrubber of the player so you can jump right to the relevant words.

![Sample Player](/docs/sample_player.png?raw=true "Sample Player")


If you're using the videojs player, we also have a plugin for that here: https://github.com/Clarify/videojs-clarify-annotations


Demo Page
---------

This demo includes a basic search page with the video player. It uses the Clarify PHP library, available here: https://github.com/Clarify/clarify-php

To use this:

*  Download this package from Github;
*  Rename credentials-dist.php to credentials.php and add your API key;
*  Run `` composer install `` to get the required PHP library;
*  Load this folder in your favorite browser, the URL will be something like: http://localhost/clarify-video-player/
*  Fill in your search terms and hit submit;
*  If you need videos, load what you need from here: http://media.clarify.io/

Note: If there are no search results, the player does not display. We should improve that.

More quickstarts are available here: http://docs.clarify.io/quickstarts/
