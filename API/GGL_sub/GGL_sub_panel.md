# Class GGL_sub_panel

A static object which displays a panel, an icon and a text.

# Relevant Methods

## Draw_sprite_at(sprite, image_index, x, y, scale_x, scale_y, color, shadow_thickness)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   sprite      | sprite id  |        the id of the sprite to draw     |
|   image_index      | integer  |      the image_index of the sprite to draw          |
|   x         | real    |      the x position to draw the sprite at    |
|   y         | real    |       the y position to draw the sprite at   |
|   scale_x    | real   |     horizontal scale       |
|   scale_y    | real   |    vertical scale   |
|   color      | color   |          the tint of the sprite   |
|   shadow_thickness    | integer   |   the thickness of the shadow behind the sprite  |

| Returns:  | N/A |
|--         |                             --|

Use this method to draw sprites with a shadow behind them.

# Variable Declarations:

- **desired_width"  => the desired width of the panel when scaled to min	(in pixels)
- **desired_height" => the desired height of the panel when scaled to min	(in pixels)
- **clicked"        => has the instance been clicked?
- **color_icon"     => the color of the icon
- **color_panel"    => the color of the panel
- **mouse_hover"    => is the mouse above the panel?
- **sprite_icon"    => the sprite of the icon
- **shadow_panel"   => the thickness of the panel's shadow

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Struct%20Classes.md)
