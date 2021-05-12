# Class parent_GGL_slider_V

** This slider is VERTICAL only **
	
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

| Returns:  |  the value of the slider |
|--         |                                                        --|

Returns the value of the slider

## Set_value(new_value)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|  new_value  |   real or integer   |  sets the new value of the slider    |

| Returns:  |         N/A |
|--         |                             --|

Sets the value of the slider

## Set_value_range(new_min, new_max)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|  new_min  |   real or integer   |  sets the new minimum value of the slider    |
|  new_max  |   real or integer   |  sets the new maximum value of the slider    |

| Returns:  |         N/A |
|--         |                             --|

Sets the range of possible values of the slider

## Set_value_type(pType)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|  pType  |   enum   |  an enum entry (e_GGL_value_type.decimal or e_GGL_value_type.integer)    |

| Returns:  |         N/A |
|--         |                             --|

Sets the type of value (decimal or integer)

# Variable Definitions:

![var_def](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/API/GGL_instance/parent_GGL_slider.png)

- **sprite_button**  => the sprite of the button
- **sprite_panel**   => the sprite of the panel
- **sprite_progBar** => the sprite of the progression bar
- **color_progBar**  => the color of the progression bar
- **value_max**      => maximum value of the slider
- **value_min**      => minimum value of the slider
- **value_type**     => type of value (decimal or integer)

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Classes.md)
