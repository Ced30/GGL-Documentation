# Class parent_GGL_draggable_animated

Same as the draggable element, except this one can have animated sprites and uses an outline shader when "mouse_hover" is set to true.
You can set the color of the outline ine the variable definitions.

# Relevant Methods

## Activate()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   N/A      | N/A  |  N/A    |

| Returns:  | N/A |
|--         |                             --|

Override this method with the "activate_override" variable in the variable definitions tab to run your own functions when the button is clicked.

## Get_value()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|  N/A  |   N/A   |  N/A    |

| Returns:  |  the "value" variable, which can store any type of value |
|--         |                                                        --|

Returns the "value" variable

## Set_value(new_value)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|  new_value  |   any   |  this variable can store any type of value    |

| Returns:  |         N/A |
|--         |                             --|

Stores any kind of value inside the "value" variable (this in conjonction with the "Activate" function can make each button unique in functionality)

# Variable Definitions:

![var_def](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/API/GGL_instance/parent_GGL_draggable_animated.png)

- **color_outline** => the color of the outline
- **outline_width** => the width of the outline

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Classes.md)
