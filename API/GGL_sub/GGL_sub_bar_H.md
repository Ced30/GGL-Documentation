# Class GGL_sub_bar_H

** This bar is HORIZONTAL only **

This class is composed of:
- 1 background panel
- 1 interpolated progression bar 
- 1 normal progression bar

The progression is set by the "value" variable, and the maximum by the "value_max" variable.
It can be used as progression bar of health bar.

# Relevant Methods

## Get_value()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|  N/A  |   N/A   |  N/A    |

| Returns:  |  the value of the progression bar (stored inside the "value" variable) |
|--         |                                                        --|


## Set_value_max(new_value)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   new_value      | real  |   the new value of "value_max"   |

| Returns:  | N/A |
|--         |                             --|

Sets the new value of "value_max"

## Set_value_type(pType)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|  pType  |   enum   |  an enum entry (e_GGL_value_type.decimal or e_GGL_value_type.integer)    |

| Returns:  |         N/A |
|--         |                             --|

Sets the type of value (decimal or integer)


## Shake(duration, intensity)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   duration      | real  |   the duration of the shake effect   |
|   intensity      | real  |   the intensity of the shake effect   |

| Returns:  | N/A                           |
|--         |                             --|

Use this function to make the drawn value shake.

# Variabl Definitions:

- **color_progBar1**      => the color of the progression bar (before)
- **color_progBar2**      => the color of the progression bar interpolated (behind)
- **is_shake**            => does the text shake when "value" is low?
- **panel_rect**          => the panel's bounding box
- **shake_current**       => new Vector2_zero();
- **shake_duration**      => the duration of the text shake
- **shake_intensity**     => the intensity of the text shake
- **shake_remaining**     => the remaining shake before it ends
- **speed_interp**        => the speed of the interpolation
- **sprite_panel**        => the panel's sprite
- **sprite_progBar**      => the progression bar's sprite
- **value_normalized**    => normalized "value", between 0 and 1
- **value_normal_interp** => normalized "value" inerpolated
- **value_max**           => the maximum value
- **value_type**          => the type of value to output (decimal or integer)
- **shake_threshold**     => the threshold before the text starts to shake (ex: 0.3 for 30% of the bar)

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Struct%20Classes.md)
