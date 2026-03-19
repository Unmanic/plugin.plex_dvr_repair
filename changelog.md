**<span style="color:#56adda">0.0.2</span>**
- Fix MKV outputs to be written as normal finished Matroska files instead of live-style MKV streams
- Remove live/cluster muxing flags that interfered with duration and seekability in Plex playback
- Keep timestamp normalization focused on repair and playback stability with `-avoid_negative_ts make_zero`

**<span style="color:#56adda">0.0.1</span>**
- Initial version
- Adds Plex DVR copy-fragment detection, grouping, repair stitching, chapter preservation, and cleanup controls
