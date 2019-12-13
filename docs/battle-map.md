[icon-pencil]: icons/pencil.png 
[icon-highlighter]: icons/highlighter.png
[icon-eraser]: icons/eraser.png
[icon-undo]: icons/undo.png
[icon-move]: icons/move.png
[icon-move-restricted]: icons/move-restricted.png
[icon-move-restricted2]: icons/move-restricted2.png
[icon-select]: icons/select.png
[icon-snap]: icons/snap.png
[icon-reveal]: icons/reveal.png
[icon-hide]: icons/hide.png
[icon-layers]: icons/layers.png
[icon-markers]: icons/markers.png 
[icon-settings]: icons/settings.png
[icon-share]: icons/share.png
[icon-fog-free]: icons/fog-free.png
[icon-fog-rect]: icons/fog-rect.png
[icon-add]: icons/add.png

# Battle Map

## Toolbar Buttons

* ![pencil][icon-pencil] Pencil
* ![highligher][icon-highlighter] Highlighter
* ![eraser][icon-eraser] Eraser
* ![undo][icon-undo] Undo
* ![move][icon-move] Move
* ![select][icon-select] Select
* ![layers][icon-layers] Layers
* ![snap][icon-snap] Snap to Grid
* ![reveal][icon-reveal] Fog of War
* ![markers][icon-markers] Markers
* ![settings][icon-settings] Setting

## Settings

* **Fog of War** - show or hide a portion of the map.
* **Line of Sight** - show or hide a portion of the map dynamically, based on vision and sight.
* **Grid Visible** - show or hide a grid on the map.
* **Grid Color** - color for grid lines.
* **Grid Size** - the size of one grid square.
* **Offset X** - grid offset on the x-axis.
* **Offset Y** - grid offset on the y-axis.
* **Image** - background image.
* **Video** - background video.
* **Scale** - background image/video scale.
* **Walls Generator** - auto walls generator.
* **Reset** - reset to defaults.

## Layers

Battle Map contains several specialized layers used for various purposes.

* **DM** - drawings placed here are visible only on the GM screen.
* **Token** - Character and Creature tokens.
* **Object** - default layer for drawings and *Map Objects*.
* **Map** - background map image or video.
* **Wall** - walls, doors, and other obstacles used in [Line of Sight](line-of-sight).
* **Floor** - used for pathfinding and the *Walls Generator*.

## Token Visibility

Token visibility can be configured in **Settings: Visible Tokens**.

## Scrolling and Zooming

1. Tap ![move][icon-move].
2. Use a finger anywhere on the map to scroll or two fingers (pinch gesture) to zoom.

## Moving Creatures

### Moving a Single Creature

1. Tap ![move][icon-move].
2. Use a finger on a circle token to move a creature anywhere on the grid.

### Moving Multiple Creatures at Once

1. Tap ![select][icon-select].
2. Use finger to select a group of creature tokens by dragging a rectangle over them.
3. Use a finger on any circle token in a selected group to move creatures anywhere on the grid.

*PRO TIP: You can choose multiple party movement modes from **Settings: Party Movement Mode**, which applies when selecting and moving a group of Characters.*

### Snap to Grid

1. Tap ![snap][icon-snap] to toggle between Snap to Grid modes.
2. Use a finger on circle token to move creature anywhere on the map.

*PRO TIP: Snap to Grid also affects **Handwriting** and **Highlighting** (see below).*

### Restricting Character Token Movement

* Tap ![move][icon-move] twice.
	* Tap ![move-restricted][icon-move-restricted2] to prevent Character tokens from crossing [Walls](line-of-sight).
	* Tap ![move][icon-move] to allow free Character token movement.

## Grid and Background Image

You can use any image as a background for your map. If your map image already contains a grid, you may need to do an alignment.

### Adding Background Image

1. Tap ![settings][icon-settings].
2. Tap **Image** and choose *Photo Library* or *Browse Files*.
3. Pick an image from your photo album or files app.

### Aligning Grid to Background Image

* Use **Grid Size** to match the square size on the background image.
* Use **Offset X** and **Offset Y** to match grid offset on the background image.
* Use **Scale** to fine-tune background image scale for better grid alignment.

<video src="https://encounter.plus/videos/grid-align.mp4" width="100%" controls preload></video>

## Line of Sight

You can use *Line of Sight* to dynamically hide a portion of the map from Players based on their vision while presenting on the external screen.

More info in dedicated [section](line-of-sight).

## Fog of War

You can use *Fog of War* tools to hide a portion of the map from players while presenting on the external screen or using Share tool.

### Enabling Fog of War

1. Tap ![settings][icon-settings].
2. Enable Fog of War.
	* ![reveal][icon-reveal], ![hide][icon-hide] Fog tools are visible on the toolbar.
	* Everything is hidden by default.

### Revealing Area

1. Tap ![reveal][icon-reveal].
2. Draw a shape on the map.
3. Tap anywhere inside shape to reveal.

### Hiding Area

1. Tap ![hide][icon-hide].
2. Draw a shape on the map.
3. Tap anywhere inside shape to hide.

### Changing Hide/Reveal Mode

Tap ![reveal][icon-reveal] or ![hide][icon-hide] twice.

### Changing Drawing Mode

* Tap ![reveal][icon-reveal] or ![hide][icon-hide] twice.
	* Tap ![fog-rect][icon-fog-rect] for rectangle drawing.
	* Tap ![fog-free][icon-fog-free] for freehand drawing.

## Markers

You can add custom markers to describe specific locations on the map.

### Adding Markers

1. Tap ![markers][icon-markers].
2. Tap ![add][icon-add] to add new marker.

*PRO TIP - Double-tap anywhere on the map to quickly add a new marker.*

### Editing Marker

1. Tap on existing marker twice.
2. Tap on *Edit* option.

### Deleting Marker

1. Tap on existing marker twice.
2. Tap on *Delete* option.

### Marker Settings

* **Name** - floating text above.
* **Label** - the character inside.
* **Color** - the main color.
* **Shape** - custom shape.
* **Size** - size, relative to grid.
* **Content** - text description.
* **Hidden** - hidden when displaying on the external screen or using Share tool.
* **Locked** - locked movement.
* **Position** - position on the map.

## Handwriting and Highlighting

You can draw on a map to highlight a specific area, add environmental effects, or sketch a basic dungeon.

### Adding Handwriting

1. Tap ![pencil][icon-pencil] or ![highlighter][icon-highlighter].
2. Use a finger or stylus to write, sketch or highlight.

### Changing Ink Color, Size, or Style

1. Tap ![pencil][icon-pencil] or ![highlighter][icon-highlighter] twice.
2. Select color, size, or style.

### Erasing Handwriting

1. Tap ![eraser][icon-eraser].
2. Tap a handwritten stroke to erase it.

### Snap to Grid

Use ![snap][icon-snap] to toggle Snap to Grid mode for drawing. Note that *Freehand* does not snap to grid.

### Undoing Handwriting

Tap ![undo][icon-undo] to undo your latest handwriting.

### Scrolling While Handwriting

Use two fingers to scroll and zoom.

## Working with Assets

See [Working with Assets](assets).
