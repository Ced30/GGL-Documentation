## Class prefab_GGL_container_panel

This is a container panel with a draggable surface draw onto it.
		Pass a sprite to the "parameters" variable (with the "Set_parameters()" method)
		or directly after dragging the instance into a room via the "variables" tab.
		
This sprite will be drawn onto a surface and cropped to the instance dimensions.
		
Once the mouse is on the panel, you can drag the sprite around by maintaining right click and run the "Activate" function by left clicking
		
Note that you can set the scale of the image with the "scale_surface" variable.
		
The image uses the icon's color and alpha when drawn (because we don't need to 
		draw an icon on top, so, they're available)

## Relevant Methods

## Activate()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   N/A      | N/A  |  N/A    |

| Returns:  | N/A |
|--         |                             --|

Override this method with the "activate_override" variable in the variable definitions tab to run your own functions when the panel is clicked.

## Set_parameters(pSprite)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   pSprite      | sprite  |  a sprite to display on the panel's surface    |

| Returns:  | N/A |
|--         |                             --|

Use this method to set the sprite to be displayed on the surface

# Variable Definitions:

![var_def](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/API/GGL_instance/prefab_GGL_container_panel.png)

- "scale_surface" => the scale of the sprite displayed on the surface

## [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Prefabs.md)

