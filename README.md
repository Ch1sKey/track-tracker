# Foundry Virtual Tabletop - Track-Tracker module

This module for [Foundry Virtual Tabletop](http://foundryvtt.com) adds new functionnalities to the Playlist Sidebar.

It's main purpose is to display a progression tracker for each currently playing track.
It also adds some other related features and, as a result, changes the overall layout of the "currently playing" pannel.

Other features include a mute button and a mark-in / mark-out system (to only play selected parts) available from the context menu.
The current time is displayed in a tooltip over the tracker.

Basically, goes from this :
![before](./images/before.png)
to this :
![after](./images/after.png)


⚠ Might be unfriendly to the build-in fade system when trying to use marks AND fade.
⚠ Once a mark-in has been added, clicking the tracker before the mark won't let your hear the beginning of the track and will resume playback from the mark in.
Clicking after a mark-out however, should work.
⚠ Still some unwanted behavior/bugs when updating a sound while it's playing.

Just tested locally in a web browser so might not work at all ^^.
