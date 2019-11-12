# Spotify to SongWhip to Viber
create a SongWhip share in Viber from Spotify using Automator on Mac

this a prototype Mac workflow, see TODOs below

prerequisites:

- create a mac app in Chrome from www.songwhip.com and save it as SongWhip.app
- Spotify and Viber installed
- enable Accesibility services for these 3 apps above in System Prefenrences
- download this Automator workflow and assign a keyboard shortcut to it in System Prefenrences

workflow:

0. go to page "+ Make a link" in SongWhip app
1. select a song in Spotify by clicking on it
2. hit the shortcut
3. wait
4. if all is OK hit enter in Viber to send the SongWhip link

TODO

- use javascript for smarter clicking in the SongWhip app (right now it is relative position based using applescript)
