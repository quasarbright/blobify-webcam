# blobify-webcam

Live webcam feed processed through a dithering + majority-vote cellular automaton that turns the image into colorful blobs.

**[Try it live](https://quasarbright.github.io/blobify-webcam)**

## Controls

- **Palette size** — number of colors in the palette (2–64)
- **Blobiness** — how many cellular automaton steps to run; higher = bigger, smoother blobs (0–200)
- **Smart palette** — extract colors from the live frame using k-means instead of a uniform RGB cube
- **Dither** — quantization method: Nearest (hard snap) or Ordered/Bayer (dithered edges)

Click the chevron in the panel header to collapse the controls.
