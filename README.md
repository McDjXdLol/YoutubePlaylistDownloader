# YouTube Playlist Downloader

This is "YouTube Playlist Downloader" for downloading playlist via python

## Table of contents

* [Instruction](#instruction)
* [Playlist](#Playlist)
* [Information](#information)

## Instruction

1. Firstly u need to download all the files and paste them to folder
2. Secondly u need to download http://builds.libav.org/windows/release-gpl/libav-11.3-win64.7z
3. Create folder in in program folder named ffmpeg
4. Then extract libav-11.3-win64.7z\win64\usr\bin\ to ffmpeg\ 
5. Next u need to prepare ur playlist.txt file [Example](#Playlist.txt preparation)
6. Then run program and click *Download*
7. After this the program should start downloading **Don't click program otherwise it will be crash!**
8. U can check console for download progress

**This is how it's should look like**

![alt text](https://i.imgur.com/AEFCGgg.png)


## Playlist

Open chrome then enter to YouTube playlist with u want to download and open console then write:
```javascript
window.clearInterval(scroll); console.clear(); urls = $$('a'); urls.forEach(function(v,i,a){if (v.id=="video-title"){console.log('\t'+v.href+'\t')}});
```
It will be give u a full list of YouTube links. Copy them and paste to Playlist.txt 
This is example of Playlist.txt:
```text
VM964:1 	https://www.youtube.com/watch?v=12abcdefgh&list=PL_zp4vzOabcesdasB-1f7szs&index=1
VM964:1 	https://www.youtube.com/watch?v=12abcdefgh&list=PL_9pbvzOabcesdasB-1f7szs&index=2
VM964:1 	https://www.youtube.com/watch?v=12abcdefgh&list=PL_9pzvzOabcesdasB-1f7szs&index=3
VM964:1 	https://www.youtube.com/watch?v=12abcdefgh&list=PL_9pbvzOabcesdasB-1f7szs&index=4
VM964:1 	https://www.youtube.com/watch?v=12abcdefgh&list=PL_9p4vzOabcesdasB-1f7szs&index=5
VM964:1 	https://www.youtube.com/watch?v=12abcdefgh&list=PL_bp4vzOabcesdasB-1f7szs&index=6
VM964:1 	https://www.youtube.com/watch?v=12abcdefgh&list=PL_gp4vzOabcesdasB-1f7szs&index=7
...
```
This needs to be clear without spaces, else program will be crash.

## Information

Program sometimes don't download some songs so everything u need is repeat downloading this song.

**Don't click program when it's downloading otherwise it will be crashed Downloader!**
Everything that u can click or control is console.
