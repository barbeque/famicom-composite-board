# Famicom Composite Mod
A composite video and audio modification meant for original red-and-white Nintendo Famicoms.

Famicoms came from the factory with RF output, which is normally fine, but Japanese television channel frequencies don't line up with North American ones. Even though both television standards are NTSC, it can be annoying to find a VCR or television set capable of tuning into those channels.

This modification bypasses the RF modulator entirely, and taps into the composite video output coming off of the PPU (Picture Processing Unit; the video chip) of the Famicom. It then sends the video through a voltage divider to step it down to normal composite video voltage levels, and passes through a common Texas Instruments video amplifier IC.

This modification was developed as part of a Leaded Solder blog project, which you can read about in the following entries:
 - [Adding composite video to a Famicom](https://www.leadedsolder.com/2020/12/17/famicom-composite-mod-v1.html)
 - [Revenge of the Famicom composite video mod](https://www.leadedsolder.com/2021/06/15/famicom-composite-mod-v2.html)

If you like the projects, please [consider becoming a patron](https://www.patreon.com/leadedsolder). Your membership helps pay for the prototyping and development of more modifications just like this.

## Installation
TODO