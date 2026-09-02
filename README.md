# Images Website

An interactive "drag the papers" page — scattered photo and note elements that can
be picked up and moved around the screen. Built with plain HTML, CSS and
JavaScript, no framework or build step.

## Running it

Open `Crush Proj/index.html` in a browser. There is nothing to install.

## Desktop vs mobile

The drag behaviour is implemented twice, because pointer events and touch events
need different handling:

| Script | For |
| --- | --- |
| `script.js` | Desktop — mouse events |
| `mobile.js` | Touch devices |

`index.html` links `script.js` by default. **To run it on mobile, swap the script
tag to `mobile.js`.**

## Layout

```
Crush Proj/
├── index.html    Page markup
├── style.css     Layout and styling
├── script.js     Drag behaviour, mouse events
├── mobile.js     Drag behaviour, touch events
└── images/       Photos and paper textures
```

## Credit

The drag interaction is based on the "Drag Papers" CodePen, reworked with its own
assets and a separate touch implementation.
