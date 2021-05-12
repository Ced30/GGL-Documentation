# Class GGL_sub_grabbable

Same as GGL_sub_button, except, you can grab it	and move it across the room if after clicking left while the mouse is above the panel.

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

- **distance** => the distance from the position of the instance and the mouse GUI position
- **grabbed**  => is the instance grabbed?
- **position_pre**  => stores the position before moving

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Struct%20Classes.md)
