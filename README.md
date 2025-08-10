Set-VideoMediaLang
==================

Powershell Cmdlet and related files for setting a video file's audio track language

What does it do?
----------------

This Powershell script may be used to run Ffmpeg on one or more video files greatly simplifying the process.  
  You may use the power of the pipeline to set all the video files in a directory to the same language. The process preserves  
  the original files by outputting updated files to another location.

What problem does this solve?
-----------------------------

Many times a video file like mp4, m4v, or mkv fails to identify the audio track language within the metadata Ffmpeg can be used to correct this,  
  However the command syntax is difficult. This Powershell script simplifies the process.

Setup
-----

\* install \`ffmpeg\` and add it to your PATH (e.g. use winget like: [https://winstall.app/apps/Gyan.FFmpeg](https://winstall.app/apps/Gyan.FFmpeg) , it'll automatically add the executable to PATH) 
or directly from ffmpeg.org at: [https://ffmpeg.org/download.html#build-windows](https://ffmpeg.org/download.html#build-windows)

\* Copy both ISO639-2\_Video\_Language\_Codes.json and Set-VideoMediaLang.ps1 to the Powershell scripts folder for your version of Powershell.