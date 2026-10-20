# Final — 8051 Music Box

For the final project, I built a small music box using an 8051 microcontroller, pushbuttons, a speaker, and a seven-segment display. The two buttons switch between three programmed songs, while the display indicates the selected track.

## Demo

**[Watch the project video on YouTube](https://youtu.be/ABH8-9qAU-I)**

[![8051 music box circuit](music-box.jpg)](https://youtu.be/ABH8-9qAU-I)

*Click the image to watch the demo.*

## How it works

- **INT0 / INT1:** handle the next/previous song buttons.
- **Timer 0:** controls the timing of each note.
- **Timer 1:** toggles the speaker output.
- **Seven-segment display:** shows the selected song number.
- **Song tables:** hold the note data for the three songs.

The original report identifies the songs as 小蜜蜂 (Little Bee), 兩隻老虎 (Two Tigers), and 大象 (Elephant).

## Project files

- [Assembly code — `music-box.a51`](music-box.a51)
- [Final report — `music-box.pdf`](music-box.pdf)
- [Extra song tables](../references/song-tables.md) (reference material, not part of the final program)

The assembly source is the original submitted version and has not been recompiled or modified for this repository.

[Back to main page](../README.md)
