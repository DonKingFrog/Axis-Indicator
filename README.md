# Axis-Indicator
This is a repository for the Roblox Plugin, Axis Indicator, and its stylesheets.


## Inserting 
To **insert a stylesheet**, you can press the **Style** button given within the plugins tab. Then locate your **JSON file**, and press **Open**.


## Writing Custom Stylesheets
To write your custom stylesheet, you'll need to know the requirements and limitations of the JSON code as of now.

* shapes, you're only able to use: `none, ball, block` (Excluding Pivot)
* color, you're supposed to write it in RGB format: `R, G, B`

UserSettings currently only has two values, coordinate which is a boolean, and scale which is a string of X and Y.

### Coordinate
This boolean value will display your current viewport position using the Camera position and your axis coloring.
You can write a custom position by pressing on the coordinate text to move your camera to that location.

### Scale
This string value will scale depending on the input x and y in the format: "0x0"
