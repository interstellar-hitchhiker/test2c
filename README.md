# DnB MeltFlow VR

DnB MeltFlow VR is a browser-based music visualiser built around Butterchurn, a WebGL version of the classic MilkDrop visual engine. It runs as a single HTML file and loads its visual engine, preset packs, and radio streams through CDN/network links, making it easy to upload to GitHub Pages and open in a normal browser or Meta Quest Browser.

The main 2D version works as a full-screen radio visualiser: choose a station, browse hundreds of MilkDrop-style presets, randomise the visuals, or let the app auto-morph between presets. It includes Bassdrive, SomaFM ambient/downtempo streams, local audio support, brightness controls, preset filters, and a hidden-controls viewing mode.

The VR mode is an experiment in taking a 2D Butterchurn canvas and mapping it into WebXR. The project went through several tests: first proving Butterchurn could run alone in the browser, then adding radio playback, then trying a curved VR screen, then a fixed dome, and finally a live inside-facing sphere. The final VR version renders the Butterchurn canvas continuously onto the inside of a sphere so the user can sit inside the visual field on a Meta Quest headset.

This is not true stereo VR180 or a native 3D visual engine. It is a practical browser hack: a live 2D MilkDrop-style canvas stretched into a VR environment. Some presets look better than others, but the experiment proves that Butterchurn visuals can run, animate, switch presets, stream music, enter/exit WebXR, and wrap into an immersive Quest browser experience from a single GitHub Pages HTML file.
