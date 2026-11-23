# Haptastic

Things to touch: squishy, clacky, satisfying toys that run in your browser, by Nelu Radpour (Florida State University).
A sister site to [VisualStims](https://nelurad.github.io/visualstims/) (brain science to look at) and [SoundBites](https://nelurad.github.io/soundbites/) (things to play and listen to).

Live at https://nelurad.github.io/haptastic/

Each toy is a folder with an `index.html` and a 900×600 `thumb.jpg`, listed on the root `index.html`. The front page hero is a sheet of bubble wrap to pop.

| No. | Toy | What it is |
|---|---|---|
| 1 | [Lump](lump/) | A ball of clay to play with in 3D: drag to press it in, hold then drag to pull it out, smooth it, spin it on a pottery wheel, pick a clay colour. Built with three.js. |
| 2 | [Clack](clack/) | A Newton's cradle in 3D. Grab and pull balls (pulling the 2nd brings the end one along; one finger per side for both at once), flick to throw, orbit the camera. Real impulse physics: one in, one out; two in, two out; with realistic losses it settles into everything swinging together. Chrome, gold, glass or rainbow (anodised) balls, 2–9 balls, one 3× heavy ball, Earth/Moon/Jupiter gravity, slow-mo and hold-space bullet time (the clack slows down too), perpetual mode, x-ray (velocity arrows, momentum glow), synthesised clacks and phone haptics. three.js + Web Audio. |
| 3 | [Skip](skip/) | Skip a stone across a lake at golden hour. Flick up to throw (speed = flick speed, aim = flick direction), set the stone's tilt (20° is the magic angle from Clanet, Hersen & Bocquet, *Nature* 2004), flat stone or round pebble. Skips happen only when the stone is fast and shallow enough; each one costs speed, so the hops shrink to a pitter-patter before it sinks. Shader water with layered waves, sun glitter, Fresnel sky reflection, shallows and spreading ripple rings; splash droplets, a follow camera, plip/plunk sounds, lake ambience, haptics, best score. three.js + Web Audio. |

Lump moved here from VisualStims in November 2026; the old address redirects.
