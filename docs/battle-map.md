[icon-pencil]: icons/pencil.png 
[icon-highlighter]: icons/highlighter.png
[icon-eraser]: icons/eraser.png
[icon-undo]: icons/undo.png
[icon-move]: icons/move.png
[icon-move-restricted]: icons/move-restricted.png
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

# Battle Map

## Toolbar buttons

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
* **Line of Sight** - show or hide a portion of the map, dynamically based on vision and sight.
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

Battle map contains several specialized layers for various purposes.

* **Tokens & Objects** - default layer for drawings and tokens.
* **Walls & Obstacles** - walls, doors and other obstacles used in [Line of Sight](line-of-sight).
* **Walkable Floors** - used for pathfinding and walls generator.

## Token Visibility

Token visibility can be configured in Settings: Visible Tokens.

## Scrolling and Zooming

1. Tap ![move][icon-move].
2. Use a finger anywhere on the map to scroll or two fingers (pinch gesture) to zoom.

## Moving Creatures

### Moving single creature

1. Tap ![move][icon-move].
2. Use a finger on circle token to move creature anywhere on the grid.

### Moving multiple creatures at once

1. Tap ![select][icon-select].
2. Use finger to select a group of creatures by dragging rectangle over them.
3. Use a finger on any circle token in a selected group to move creatures anywhere on the grid.

*PRO TIP: You can choose multiple party movement modes from app settings, which applies when selecting and moving a group of players*

### Snap to Grid

1. Tap ![snap][icon-snap] to toggle between snap to grid modes.
2. Use a finger on circle token to move creature anywhere on the map.

## Grid and Background Image

You can use any image as a background for your map. If your map image already contains a grid, you need to do an alignment.

### Adding background image

1. Tap ![settings][icon-settings].
2. Tap **Image** and choose Photo Library or Browse Files.
3. Pick an image from your photo album or files app.

### Aligning grid to background image

* Use **Grid Size** to match the square size on the background image.
* Use **Offset X** and **Offset Y** to match grid offset on the background image.
* Use **Scale** to fine-tune background image scale for better grid alignment.

<video src="https://encounter.plus/videos/grid-align.mp4" width="100%" controls preload></video>

## Line of Sight

You can use *Line of Sight* to dynamically hide a portion of the map from players based on their vision while presenting on the external screen.

More info in dedicated [section](line-of-sight).

### Walls generator

You can use *Walls Generator* tool to quickly generate walls and obstacles for Line of Sight based on walkable floors. It’s ideal for dungeons with rectangular corridors.

1. Tap ![settings][icon-settings].
2. Tap *Walls Generator*.
3. Adjust parameters.
	* **Wall Offset** - offset from other side of wall.
	* **Floor Color** - only use floors with selected color.
	* **Continuous** - if enabled, each wall will be generated as a single continuous line, otherwise it will be divided into separate segments.
4. Tap Generate.

*Pro TIP - You can experiment with parameters by using this tool multiple times. All previously generated walls will be replaced.*

## Fog of War

You can use *Fog of War* tools to hide a portion of the map from players while presenting on the external screen or using Share tool.

### Enabling fog of war

1. Tap ![settings][icon-settings].
2. Enable Fog of War.
	* ![reveal][icon-reveal], ![hide][icon-hide] Fog tools are visible on the toolbar.
	* Everything is hidden by default.

### Revealing area

1. Tap ![reveal][icon-reveal].
2. Draw a shape on the map.
3. Tap anywhere inside shape to reveal.

### Hiding area

1. Tap ![hide][icon-hide].
2. Draw a shape on the map.
3. Tap anywhere inside shape to hide.

### Changing hide/reveal mode

1. Tap ![reveal][icon-reveal] or ![hide][icon-hide] twice.

### Changing drawing mode

1. Tap ![reveal][icon-reveal] or ![hide][icon-hide] twice.
	* Tap ![fog-rect][icon-fog-rect] for rectangle drawing.
	* Tap ![fog-free][icon-fog-free] for freehand drawing.

## Markers

You can add custom markers to describe specific locations on the map.

### Adding markers

1. Tap ![markers][icon-markers].
2. Tap + to add new marker.

*Pro TIP - Double Tap anywhere on the map to quickly add a new marker.*

### Editing marker

1. Tap on existing marker twice.
2. Tap on *Edit* option.

### Deleting marker

1. Tap on existing marker twice.
2. Tap on *Delete* option.

### Marker settings

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

### Adding handwriting

1. Tap ![pencil][icon-pencil] or ![highlighter][icon-highlighter].
2. Use a finger or stylus to write, sketch or highlight.

### Changing ink color, size, or style

1. Tap ![pencil][icon-pencil] or ![highlighter][icon-highlighter] twice.
2. Select color, size, or style.

### Erasing handwriting

1. Tap ![eraser][icon-eraser].
2. Tap a handwritten stroke to erase it.

### Undoing handwriting

1. Tap ![undo][icon-undo] to undo your latest handwriting.

### Scrolling while handwriting

* Use two fingers to scroll and zoom.

## Working with Assets

<div class="video">
    <iframe  src="https://www.youtube.com/embed/V-BUZvcmO5Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>