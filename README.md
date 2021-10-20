# spotify-playlist-downloader 🎵


1. Open cmd/console
2. Clone repo by `git clone git@github.com:Shubhamrawat5/spotify-playlist-downloader.git`
3. Open directory by `cd spotify-playlist-downloader`
4. Run `npm install` to install all dependencies

> This uses puppeteer to extract spotify playlist info so it'll download chromium (150-200mb)

5. Now edit playlist url variable and set your playlist link in file `downloader.js [line 5]`
6. Run `node app.js`

- Now a folder named "songs" will be created.

- Playlist info will be extract and all the matching songs will start donwloading!

- If by chance you stop the script in between, then no worries as if song is already downloaded then next time it won't be downloaded again!

- Also there is 5% chance that song's some remix or different same name song will get downloaded...


### Screenshots 🚀

<img src = "https://i.ibb.co/ScGmnj3/download-spotify-to-mp3.png" width="350"/>
<img src = "https://i.ibb.co/0MfLvNy/spo.png" width="800"/>
