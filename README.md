# efootball-server-quality-detector
Free Windows tool for monitoring eFootball server connection quality. Download the latest version from Releases.
## Why I Built This

I began developing eFootball Server Quality Detector about two years ago. The project grew from analyzing millions of network synchronization data points between players and game servers.

For online peer-server-peer (PSP) matches, I found that the first ten seconds of synchronization can provide an important early indication of connection quality. In my observations, when synchronization is poor from the start, around 90% of those matches continue to experience one-sided lag or input delay for much of the match.

This is an observation based on my own data and testing. It is not a guarantee for every match or an official measurement from Konami. The detector is intended to help players assess the connection early and decide whether to continue or cancel the match, select higher score as much as you can from beginning.  

Currently, this detector is available only for the Windows PC version of eFootball, including gameplay launched through Steam or the Xbox app.

The software is free to use. If you find it useful, you can optionally support its development on [Ko-fi](https://ko-fi.com/angganurdiansah).

## Connection Recommendations

- For a stable connection, use a wired Ethernet connection with a Cat 6 cable or higher.
- For recommended LAN adapter settings, see [this guide](https://www.youtube.com/watch?v=mEoXW-SH-y0).

## Other Factors That May Affect Synchronization

Synchronization can also be affected by peak-hour network congestion, game-server load, and your internet service provider (ISP). These conditions are outside the detector’s control.
