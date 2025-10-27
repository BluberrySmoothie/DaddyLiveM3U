## Support the Project
If you like my work, feel free to buy me a coffee! ☕
https://buymeacoffee.com/BluberrySmoothie


# DaddyLiveM3U
Re-streamer of DaddyLive channels

Save both files in the same folder..
Run app.py

M3U for your IPTV software will be avaliable at: http://<<Machine IP>>:5000/daddylive/live_tv.m3u

You can run this on a PC, Raspberry Pi or anything on your home network that supports Python and FFMPEG. Once running, the M3U will be avaliable to any device on your home network.

**Changes in latest version:**

Added "DLConfig.db" -- This allows you to map the DL channel to an output M3U file. You can also map your EPG data (XML or Gracenote) and channel logos. It also allows you to over-ride the output channel number and channel name. I didn't add any front end tool to update the SQLite DB (yet). You'll have to do this via the DB management tool of your choosing.

The DL Channel and DL Name are automatically updated every 12 hours in the DB. Also added a button to the admin page allowing to force refresh.

Live events now has a matching XML TV Guide.
