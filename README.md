# Click Joints

A Blender add-on that turns a sculpt into a poseable, printable figure. Set the 3D cursor where the joint goes, click **Place joint**, and Click Joints cuts the mesh into two watertight parts with a ball and socket or a pin, sized with the clearance your printer needs, in millimetres.

For a ball joint it measures how far the joint bends before the parts collide, in 8 directions, and shows that range in the viewport. A ring on the cut shows the fit: green is good, yellow is tight, red is too thin or breaks through the surface.

- Measured bend range of every ball joint, in degrees, before you print
- Ball and socket, or pin and hole
- Auto size: picks the largest ball with a good fit, or tells you when none fits well
- Clearance in mm (0.1 to 0.3 mm is typical)
- Exploded view; the export stays in place
- "Make watertight" for open or messy meshes, on a copy
- Export as STL or 3MF, one file per part, in millimetres
- Tested on Blender 4.2 LTS, 5.2 LTS and 5.3

Current version: 0.1.1 (a joint in one knee no longer cuts through the other leg).

## Install

Get it from the Blender Extensions platform (Edit > Preferences > Get Extensions, search "Click Joints"), or download the zip from the releases and use Install from Disk.

## Click Joints Pro

Need knees and elbows that bend one way and stop? Click Joints Pro adds a printable click hinge with an end stop at 90°, 115° or 135°, a pose slider per hinge, red marks on both parts when you pose past the stop, and spacing checks. Everything in the free version is included.

Personal license $12, studio license (up to 5 people) $45, all Pro 1.x updates included: https://duinhouwer8.gumroad.com/l/click-joints-pro

The free Click Joints stays free and keeps getting fixes.

## Report a problem

Open an issue here: https://github.com/thijsduinhouwer2002-coder/click-joints/issues

Please include your Blender version, what you clicked, and the message the panel showed. A small .blend file helps a lot.

Email: thijs@dortus.com

## License

GPL-3.0-or-later. See [LICENSE](LICENSE).
