# SPAR project page

Project page for SPAR (Scene-grounded Pose And track Refinement). Code is in `20af02/SPAR`.

Preview locally with `python3 -m http.server 8000` and open http://localhost:8000.

Videos go in `static/videos`. Encode them with
`ffmpeg -i in.mp4 -an -c:v libx264 -crf 24 -pix_fmt yuv420p -movflags +faststart out.mp4`.

The layout is adapted from the [Nerfies](https://github.com/nerfies/nerfies.github.io) template (CC BY-SA 4.0).
