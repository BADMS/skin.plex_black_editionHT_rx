Get from GitHub here: https://github.com/BADMS/skin.plex_black_editionHT_rx


Studio Logos here and go in /skin.plex_black_editionHT_rx/media/studiologos

https://www.dropbox.com/s/p9nhotegprax3w1/studiologos.7z?dl=0
 

TV Logos here and go in /skin.plex_black_editionHT_rx/media/tvlogos

https://forums.plex.tv/index.php/topic/106378-release-night-skin-for-pht-v173/#entry629497

 
Custom URL shortcuts how to

https://forums.plex.tv/index.php/topic/130576-plex-black-edition-remix/page-2#entry797676
 

2015-01-09

- COMMITTED TO GITHUB PLEASE CHECK THERE FROM NOW ON


SHORTCUTS HOW TO

First 3 channels need a plugin name ie. youtube, iplayer, iTunes, vimeo, lmwt etc (get from plex logs or plugin dir .py code)

Next 3 use complete URL (Of course Plex (Windows Kodi) doesn't let you paste in keyboard box....)

OK,so here we go.

Get this: http://www.hot-keyboard.com/docs/paste_help.htm

Enable PHT debug logging, start PHT and go to the channel and where you want shortcut to link to.

Close PHT, goto log and find the URL, something like this:

15:31:13 T:4516   DEBUG: CPlexFilterManager::loadFiltersFromDisk loading filters for section plexserver://be947b30de7253zzzzzzcb4fc15db35684dffb09/video/youtube/parsefeed?url=http%3A%2F%2Fgdata.youtube.com%2Ffeeds%2Fapi%2Fstandardfeeds%2FREGIONID%2Fmost_viewed%3Ftime%3Dtoday&title=Most+Viewed

then we need this bit plexserver://be947b30de7253zzzzzzcb4fc15db35684dffb09/video/youtube/parsefeed?url=http%3A%2F%2Fgdata.youtube.com%2Ffeeds%2Fapi%2Fstandardfeeds%2FREGIONID%2Fmost_viewed%3Ftime%3Dtoday&title=Most+Viewed

Open Hot app, new macro, choose paste, paste your URL, choose hot key. Repeat for others.

Enter PHT settings, channels, use URL type channels, use hotkey to paste. Done!
