# yt-supersubs
Simple proof of concept for adding custom .srt files to play in sync with embedded youtube videos

<img width="865" alt="yt-supersubs" src="https://github.com/user-attachments/assets/87237521-6206-4d0c-9a27-1473c5312c79" />

Youtube discontinued community contributed subtitles in 2020.
So if you find a good video, but it doesn't have the subtitle language you want, you're stuck requiring the user to navigate through the subtitle settings to enable existing subtitles, and then select auto-translated subtitles.

There is a URL scheme to pass params to try and set existing subtitles, but it can't access auto-translated subs, and it often fails because of local user setting overrides.

This "solves" all of these issues.

Using this template, you can serve a video (or video gallery) via github pages, and syncronize with supplied .srt files.
