# Class GGL_sub_slider

A GUI slider, composed of:
- 1 background panel
- 1 progression bar
- 1 draggable button
- 1 label
- 1 value

Maintain left click while the mouse is above the button to move it along the slider panel.

You can set the min, max, of the slider, and retrieve the current value with the "Get_value" method.

The slider can use either decimal or integer values, set it in the variable definitions tab.

# Relevant Methods

## Get_value()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|  N/A  |   N/A   |  N/A    |

| Returns:  |  the "value" variable                                  |
|--         |                                                      --|

Returns the current value of the slider (the "value" variable)

## Set_value(new_value)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|  new_value  |   real   |  the new value of the "value" variable    |

| Returns:  |         N/A |
|--         |                             --|

Sets the current value of the slider

# Variable Declarations:

- **button_index**     => the image index of the button sprite
- **button_rect**      => the bounding box of the button sprite
- **button_scale**     => the scale of the button sprite
- **button_sFactor**   => the scaling factor of the button sprite
- **sprite_button**    => the sprite of the button
- **sprite_progBar**   => the sprite of the progression bar
- **panel_rect**       => the bounding box of the panel sprite
- **value_normalized** => "value" normalized between 0 and 1
- **value_max**        => maximum value of the slider
- **value_min**        => minimum value of the slider
- **value_type**       => type of value (decimal or integer)	

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Struct%20Classes.md)
