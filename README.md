# UZal ♡ Sonam Choden — 3D Memory Gallery

A mobile-friendly 3D birthday/memory game with framed photos on the gallery walls, clickable stories, a birthday-wish frame, dance, optional music, keyboard movement, a mobile movement joystick, and a separate camera-look joystick.

## Add your photos
Put your JPGs in `photos/` using the six exact filenames listed in `photos/README.md`. The frames in `index.html` already point to those paths. Upload the complete `photos/` folder to GitHub with the site. If you use other filenames, update the `image` path in the `MEMORIES` array in `index.html`.

## Change the birthday wish and messages in code
There is no edit button, no in-game editor, and no name-entry screen. Edit the `MEMORIES` array near the top of `index.html`. The birthday wish is the fifth entry, `A wish for your birthday`, and opens from the **Birthday wish** button.

## Controls
- Desktop: WASD / arrow keys move; drag the scene to rotate camera; click a frame to open its story; Space dances.
- Mobile: left joystick moves; right joystick changes camera view; tap a framed photo to read it.
- Music toggle is optional.

## Run and publish
Open `index.html` in Safari or Chrome with internet access (Three.js loads from a CDN). For GitHub Pages, upload `index.html`, `README.md`, `LICENSE`, and the `photos/` folder, then choose **Settings → Pages → Deploy from branch → main / root**.

## Privacy
Photos committed to a public repository are public. Only publish photos and messages that both people are comfortable sharing. The 3D room and avatar are stylized starter artwork.
