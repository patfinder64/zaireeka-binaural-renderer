# Zaireeka Binaural Renderer

**▶ Open the tool: https://ddrussianinja.github.io/zaireeka-binaural-renderer/**

A browser-based tool that mixes the four discs of The Flaming Lips' 1997 album *Zaireeka*, which were made to be played
at the same time on four separate stereo systems, into a single binaural track for headphones. Each disc's left and
right channels become virtual speakers placed around you in a measured room, using binaural room impulse responses
(BRIRs) from Shanon Pearce's ASH datasets.

Everything runs locally in your browser. Nothing is uploaded, and there is nothing to install.

## What you need

1. **Your own copy of the album.** The official 4-disc digital release (24-bit/44.1 kHz, DRM-free) is sold on
   [Qobuz](https://www.qobuz.com/us-en/album/zaireeka-the-flaming-lips/nxoi58i2cl4hb).
   Supported formats: FLAC (recommended), WAV, MP3, AAC/M4A and Ogg/Opus. The tool expects `Disc 1` … `Disc 4` folders,
   or `(Disc N)` in the file names.
2. **BRIRs.** Download the free [ASH Listening Set](https://github.com/ShanonPearce/ASH-Listening-Set/releases/latest)
   ("Source code (zip)"), unzip it, and choose its `BRIRs` folder. The older
   [ASH-IR-Dataset](https://github.com/ShanonPearce/ASH-IR-Dataset/releases/latest) also works.
3. **A desktop browser.** Chrome or Edge is recommended; they can save straight into a folder you choose. Firefox and
   Safari work too, but save the results to your Downloads folder instead. Phones and tablets are not supported.

## Features

- Rooms, measurement setups (dummy head, speaker distance) and, in some rooms, speaker heights from the ASH datasets
- Per-disc azimuth (separate left/right angles if you like), height, delay and direct-to-reverb level, with a top-down
  diagram of the layout
- Separate track files or one album file (with a `.cue` sheet); album or per-track normalisation
- Output as FLAC 24/16-bit or WAV 24/16/32-bit float, with tags and cover art copied from your files
- A test mode that renders only the first few seconds of each track, for trying out settings

Rendering the whole album in one go needs a few GB of free memory.

## Credits

- *Zaireeka* © The Flaming Lips / Warner Records. This tool does not include any of the album's audio.
- BRIRs: [ASH Listening Set](https://github.com/ShanonPearce/ASH-Listening-Set) and
  [ASH-IR-Dataset](https://github.com/ShanonPearce/ASH-IR-Dataset) by Shanon Pearce, which in turn credits the
  original measurement datasets. See those projects for their licenses.

## License

The tool's code is released under the [MIT License](LICENSE).
