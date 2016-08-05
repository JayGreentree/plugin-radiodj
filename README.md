# plugin-radiodj
SongPoster Plugin for [RadioDJ](http://radiodj.ro)

## What is SongPoster?
Song Poster connects your online radio station to popular social networks.

Basic functionality is posting messages to any or all of the supported platforms, mentioning Artist and Title that just played on your station.

## Where do I sign up?
Song Poster is currently in closed beta, but we're accepting new testers all the time.
If you'd like to participate, join this Google Group for further instructions:
[SongPoster testing](https://groups.google.com/forum/#!forum/song-poster-testing)

A first public and stable release is planned for Q2/2016.

## How can this plugin help?
Basically you can see this as a customized version of the official RadioDJ NowPlaying Plugin.
This version is limited to work with our service, but includes some benefits over the original plugin.

Most importantly, this plugin allows you to post only every once and a while and is not limited to posting every track:
You can decide between two interval modes:
* By minutes between two posts
* By number of songs between two posts

You can either manually configure the plugin or make it automatically load all settings from a PAL file generated by the Website.

## How to use in 10 easy steps (using auto-configuration from PAL)
1. Sign Up for the service (Currently in closed beta, [apply for the Beta Test here](https://groups.google.com/forum/#!forum/song-poster-testing))
2. Set everything up and download any of the offered PAL Scripts
  
  ![SongPoster download button](https://dl.dropboxusercontent.com/u/7370504/radioDJ/PAL-Download.png)

3. [Download the Plugin](https://github.com/songposter/plugin-radiodj/releases/download/v0.4/Plugin_SongPoster.dll)
4. Install the Plugin (put the dll file into the plugins directory and it will be available on the next start of RadioDJ)
5. Open the Options screen
  
  ![RadioDJ Main screen](https://dl.dropboxusercontent.com/u/7370504/radioDJ/Step1.png)
  
5. Click the Plugins Button in the lower right
  
  ![RadioDJ Options window](https://dl.dropboxusercontent.com/u/7370504/radioDJ/Step2.png)

6. Select SongPoster in the list
  
  ![RadioDJ Options window](https://dl.dropboxusercontent.com/u/7370504/radioDJ/Step3.png)

7. Either double-click the entry or hit the Settings or Show button
 
8. Go right to the last tab for the automatic configuration. Load the .pal file downloaded in Step #2 from your harddisk using the Browse Button. (This will automatically fill in the caption template and General configuration fields on the first tab)
  
  ![RadioDJ Options window](https://dl.dropboxusercontent.com/u/7370504/radioDJ/Step4.png)

9. Hit the Save button to apply your settings and save them for your next session

10. From now on RadioDJ will notify the plugin every time a new track is played. If your interval configuration is matched, the Plugin will then notify the webservice to send a post to your social media accounts.

## Roadmap
- [x] Post Scheduling
- [x] Fill out the whole config from loaded PAL script
- [ ] Picture-posting from RadioDJ (AlbumArt)
