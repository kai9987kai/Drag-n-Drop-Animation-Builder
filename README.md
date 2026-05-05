# Animation Builder V3 – Experimental Animation Studio

A standalone HTML, CSS, and JavaScript animation studio for building animated scenes directly in the browser. It supports draggable shapes, text, emojis, images, keyframes, motion presets, drawing tools, particles, exports, local saves, and timeline playback.

## Features

### Shape Builder

Create and edit multiple object types:

- Square
- Circle
- Triangle
- Diamond
- Star
- Blob
- Text
- Image URL objects
- Emoji objects

Each shape can be customised with:

- Position
- Width and height
- Rotation
- Scale
- Fill colour
- Border colour
- Border width
- Opacity
- Text or emoji content
- Image URL
- Flip horizontal / vertical
- Lock / unlock
- Hide / show
- Layer order

## Animation System

Animation is built using keyframes. Each keyframe stores the full visual state of the selected shape.

Stored keyframe values include:

- X and Y position
- Width and height
- Rotation
- Scale
- Colour
- Border
- Opacity
- Shape type
- Text
- Image URL
- Flip state
- Speed
- Easing

Supported easing modes:

- Linear
- Ease In
- Ease Out
- Ease In / Out
- Bounce

Playback modes:

- Once
- Loop
- Ping-pong

## Timeline Tools

The timeline lets you:

- Add keyframes
- Delete the last keyframe
- Copy keyframes
- Paste keyframes
- Scrub through keyframes
- Reverse keyframes
- Reset a timeline
- Spread one speed value across all keyframes
- Preview one shape
- Preview all animated shapes together

## Motion Presets

Built-in motion presets help create animations quickly:

- Bounce
- Spin
- Orbit
- Pulse
- Zigzag
- Entrance

The Magic Animate button randomly applies a motion preset to the selected shape.

## Scene Generators

Animation Builder V3 includes quick scene templates:

- Logo Reveal
- Space Launch
- Party Pop

These automatically add animated shapes, gradients, emojis, and particles.

## Particle Tools

The Particle Burst tool creates many animated particles around the selected object or stage centre.

You can control the particle count and then edit the generated particles like normal shapes.

## Free Draw Mode

The app includes a drawing layer on top of the stage.

Drawing features:

- Brush mode
- Eraser mode
- Brush colour
- Brush size
- Clear drawing
- Drawing saved with project
- Drawing included in PNG export

## Stage Controls

The stage supports:

- Custom background colour
- Gradient backgrounds
- Grid overlay
- Adjustable grid size
- Snap to grid
- Stage size presets
- Custom width and height

Stage presets include:

- Desktop 960×620
- HD 1280×720
- Square 1080×1080
- Story 720×1280
- Custom

## Camera and Effects

Preview-only camera tools include:

- Zoom
- Pan X
- Pan Y
- Reset camera
- Camera pulse
- Camera shake
- Vignette overlay

These help preview dramatic scene movement while keeping clean stage exports.

## Export Options

The project can export:

- JSON project file
- PNG image
- SVG image
- Sprite sheet PNG

The JSON export can be imported later to continue editing.

## Saving

Projects can be saved locally in the browser using `localStorage`.

The app supports:

- Manual local save
- Open saved project
- Autosave
- JSON import
- JSON export

Saved projects stay in the same browser unless cleared by the user.

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| Space | Play / pause active animation |
| Ctrl + S | Save project locally |
| Ctrl + D | Duplicate selected shape |
| Delete / Backspace | Delete selected shape |
| Ctrl + Z | Undo |
| Ctrl + Y | Redo |
| Arrow keys | Nudge selected shape |
| Shift + Arrow keys | Larger nudge |

On Mac, use `Cmd` instead of `Ctrl`.

## How to Use

1. Open the HTML file in a browser.
2. Add a shape using the shape buttons.
3. Select the shape on the stage or in the layers panel.
4. Move and style the shape.
5. Click **Add Keyframe**.
6. Change the shape position, size, rotation, colour, or opacity.
7. Click **Add Keyframe** again.
8. Click **Play Active** to preview the animation.
9. Use **Preview All** to play all animated shapes together.
10. Export as JSON, PNG, SVG, or sprite sheet.

## Recommended Browser

Use a modern desktop browser such as:

- Google Chrome
- Microsoft Edge
- Firefox
- Safari

Chrome or Edge are recommended for the smoothest canvas and export support.

## Notes and Limitations

- Remote image URLs may block PNG export if the image server does not allow canvas access.
- Local browser saves are stored only on the same device and browser.
- SVG export includes shapes, text, emoji, and image references, but not the free draw canvas layer.
- Camera effects are mainly for preview and do not change the exported PNG stage.
- Very large stages, many particles, or many keyframes may reduce performance on weaker devices.

## File Structure

This project is a single standalone HTML file.

It contains:

- HTML layout
- CSS styling
- JavaScript animation logic
- Timeline system
- Export tools
- Local save system

No build tools or external libraries are required.

## Project Status

Animation Builder V3 is an experimental browser-based animation studio focused on fast prototyping, creative motion, and interactive scene building.

It is designed for:

- Simple animations
- Motion experiments
- Logo reveals
- Emoji animations
- Educational animation demos
- Sprite sheet generation
- Quick social-style animated scenes

## License

Use, modify, and improve freely for personal or educational projects.
