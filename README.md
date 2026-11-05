# Video-Splicer
Trim or join MP4s without re-encoding, fast & lossless edits.

Download: https://github.com/pftq/Video-Splicer/releases/tag/20261105<br>
You may also find these useful (one-click to download all [here](https://drive.google.com/drive/folders/1nvQFC5uwsZlf-82LuskCP-qut9xHw-lt?usp=sharing)):\
• [Video Debanding](https://github.com/pftq/Video-Debanding) (fixes quality issues with repeat re-processing/compression)\
• [Video Compare](https://github.com/pftq/Video-Compare) (to check export errors, differences, etc)\
• [MP4 Audio Delay Fix](https://github.com/pftq/MP4-Audio-Delay-Fix) (20ms delay at start of file)\
• [Video Frame Sync](https://github.com/pftq/Video-Frame-Sync) (syncing 2 files that drift out of sync)\
• [Video Color Match](https://github.com/pftq/VideoColorMatch) (correcting color grading drift)\
• [Screencaps Generator](https://github.com/pftq/Screencaps-Generator) (smart screencaps selection + gallery grid sheet)

I remember other tools used to exist for this but for the life of me can't remember what they were, so this is more for my own sanity more than anything else - was easier just to quickly make this while I was already playing around a lot with FFMPEG.

<img width="1231" height="1277" alt="image" src="https://github.com/user-attachments/assets/f13ebb2d-f7bf-49b2-9efd-6fe99cac2a88" />


Credits:
- Python, application runtime
- Tcl/Tk, user interface
- Pillow, image previews
- PyAV / FFmpeg, media inspection, preview decoding, and lossless trimming/joining
- PyInstaller, Windows executable packaging
