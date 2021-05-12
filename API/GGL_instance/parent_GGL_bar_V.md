# Class parent_GGL_bar_V

This class is composed of:
- 1 background panel
- 1 interpolated progression bar 
- 1 normal progression bar

The progression is set by the "value" variable, and the maximum by the "value_max" variable.
It can be used as progression bar of health bar.

** This slider is VERTICAL only **
	
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

## Set_value_type(new_type)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   new_type      | integer  |   new_type is an enum entry   |

| Returns:  | N/A |
|--         |                             --|

Sets the "value" variable to be integer or decimal.

## Shake(duration, intensity)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   duration      | real  |   the duration of the shake effect   |
|   intensity      | real  |   the intensity of the shake effect   |

| Returns:  | N/A                           |
|--         |                             --|

Use this function to make the drawn value shake.


# Variable Definitions:

![var_def](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/API/GGL_instance/parent_GGL_progression_bar.png)

- **sprite_panel**    => the panel's sprite
- **sprite_progBar**  => the progression bar's sprite
- **color_progBar1**  => the color of the progression bar (before)
- **color_progBar2**  => the color of the progression bar interpolated (behind)
- **value_max**       => the maximum value
- **value_type**      => the type of value to output (decimal or integer)
- **is_shake**        => does the text shake when "value" is low?
- **shake_threshold** => how low does the value have to be before the text starts to shake (ex: 0.3 for 30% of the bar)

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Classes.md)
