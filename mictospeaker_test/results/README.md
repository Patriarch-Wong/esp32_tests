# Diagnostic snapshot — 2026-09-23

The two text logs contain a simultaneous 60-second capture at 115200 baud.
Both boards booted with their correct roles, AUD2 ADPCM, and Wi-Fi channel 6.
Speaker playback was 48 kHz from a 16 kHz radio stream.

The last periodic report, approximately 55 seconds after boot, recorded:

- TX: 2721 submitted, 24 busy drops, zero radio failure reports or I2S errors.
- RX: 2599 received, 146 missing, 108 underruns, zero I2S errors.
- Across logged intervals, 226 of 878400 microphone samples reached full scale.

Listening observations reported by the user after the capture:

- The synthetic tone sent from the microphone board was mostly clean with
  occasional interruptions.
- Live microphone speech was audible but overwhelmed by hiss/blowing noise.
- Sending digital silence from the microphone board removed that hiss.
- A 4 kOhm resistor reduced noise; its location has not been confirmed.

These results make microphone capture worth investigating but do not establish
whether the cause is the microphone, wiring, acoustic feedback, timing, or
sample interpretation. The actual microphone model remains unconfirmed.

Raw voice recordings, music files, build products, and machine-generated editor
files remain in the original local project and are not included here.
The SD player requires a locally supplied MP3; its bundled codec is preserved
with the upstream license and provenance.
