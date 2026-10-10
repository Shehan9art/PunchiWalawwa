VIDEOS FOLDER
=============
Put your video files (MP4 recommended, H.264) in this folder.

The Gallery page has three video slots. To activate one, open index.html,
find the slot (search for "VIDEOS:" or the slot title) and put the file path
in its data-video attribute:

  <div class="vid-slot" data-video="videos/villa-walkthrough.mp4"> ... </div>

Slot titles in order:
  1. Villa Walkthrough
  2. Pool & Gardens
  3. Garden & Pool

Leave data-video="" empty to keep the "Video coming soon" placeholder.
Use lowercase filenames with hyphens, no spaces.
Tip: keep each file under ~100 MB (GitHub's per-file limit) - compress with HandBrake if needed.
