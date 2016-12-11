# ffmpeg-binaries
A simple way to install FFMPEG globally or for an individual project.  
Supports Windows and Linux

## Versioning
The major, minor, and patch versions correspond to the version of ffmpeg this package supports.
The metadata corresponds to the version of the package itself.

## Install
### Install Globally:
`npm i -g ffmpeg-binaries`  
This will put `ffmpeg` and `ffprobe` in the path.

### Install For a Project:
`npm i ffmpeg-binaries`  
If you are on Windows his will put `ffmpeg`, `ffprobe`, and `ffplay` in `node_modules/ffmpeg-binaries/bin`  
If you are on Linux his will put `ffmpeg`, `ffprobe`, and `ffserver` in `node_modules/ffmpeg-binaries/bin`