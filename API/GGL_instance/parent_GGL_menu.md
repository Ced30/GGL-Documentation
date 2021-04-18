# Class parent_GGL_menu

A GUI element desined to build in-game menus, it can contain sub_groups of GGL_sub elements.
You can navigate through the groups by switch them on / off (with a pop-in / pop-out effect).
The label should stay empty, so you can draw the group's labels instead, and this instance doesn't require a sprite,
as we don't draw it directly.

# Relevant Methods


## Add_element(label)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   label     | string  | the label of the group that will be created |

| Returns:  | the group that's been created |
|--         |                             --|

Use this method to add new groups to the menu.


## Activate()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|    N/A      |   N/A   |                    N/A                     |

| Returns:  | N/A |
|--         |   --|

Store a room id in the "value" variable and call this method to change the menu's active group


## Set_value(new_value)
| Parameter   |  type    |              description                   |
|--           |        --|--                                          |
| new_value   | integer  | the new value of the "value" variable      |

| Returns:  | N/A |
|--         |                             --|

Use this method, combined with the "Activate" method to change the active group.

## Update_logic()
| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|    N/A      |   N/A   |                    N/A                     |

| Returns:  | N/A |
|--         |   --|

This method is called each frame, override it to run your own logic.

# Variable Definitions tab

![variable_def](%5Benter%20link%20description%20here%5D%28https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/API/GGL_instance/parent_GGL_menu.png%29)

## [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Classes.md)
