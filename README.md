# Anatomy Lab Atlas

A free, interactive 3D anatomy atlas for lab practicals. It runs in any modern browser on a phone or computer, with nothing to install.

**Live site:** https://jm2782221-ui.github.io/anatomy-lab-atlas/

## What it does

- Every bone and muscle of the human body in 3D (rotate, zoom, search, isolate)
- Tap a bone to show its marking dots; tap a dot for its definition, attachments and clinical notes
- Detailed cards for 14 shoulder and arm muscles (action, origin, insertion, innervation, blood supply)
- Pin test for bone markings, bones and muscles, with multiple choice or typed answers and a "Missed" drill
- Exam prep list with bookmarks and personal notes (saved in your browser)

## How it's built

One static page (`index.html`) using three.js, plus three compressed mesh files (`bone.txt`, `m1.txt`, `m2.txt`). It's hosted free on GitHub Pages; there is no server or account.

## Credits and licenses

3D anatomy data: [BodyParts3D](https://dbarchive.biosciencedbc.jp/en/bodyparts3d/download.html), © The Database Center for Life Science, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). The meshes were smoothed, simplified, recolored and re-packed for this atlas.

Marking positions are placed automatically on the 3D models and are approximate. This is a study aid, not a clinical reference.
