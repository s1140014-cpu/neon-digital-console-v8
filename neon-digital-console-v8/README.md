# NEON DIGITAL CONSOLE V8

Browser-based multitrack mixer prototype.

## Features
- 24 independent input strips with per-channel audio file loading and playback
- Four independently level-controlled buses with mute, AFL monitor and meters
- Per-channel multi-bus routing matrix (each channel can feed any combination of buses)
- PFL pre-fader monitor tap and AFL post-bus-fader monitor tap
- Web Audio EQ, high-pass filter, dynamics compressor, threshold gate, pan and channel fader
- Reverb convolver and editable decay/damping; feedback delay with editable time/feedback/tone/HPF
- Master peak/RMS dBFS meter, peak hold, clip warning
- Three channel layers and local browser Scene snapshots

## Run
Open `index.html` in a recent Chrome or Edge browser, click "啟用音訊引擎", then load audio files on channels.

## Important limitations
- Monitor is a separate Web Audio signal path but uses the browser's default output device; independent hardware headphone output selection is not guaranteed.
- +48V is only a UI indicator; phantom power must come from compatible hardware.
- This is a prototype, not a certified professional console. Browser latency and routing depend on the device and browser.
