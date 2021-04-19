# Class parent_GGL_container

Base button container, contains GGL_sub elements,	which are shown and interactable only if "elements_active" is set to true.
  
# Relevant Methods

## Add_element(type, label, script, x, y, w, h)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|    type     |   type id   |    the type of GGL_sub to add                   |
|    label    |   string   |     the label of the GGL_sub we're adding             |
|    script   |   script id   |    the "Activate" function we're passing         |
|    x        |   real   |     the x position of the GGL_sub relative to the container      |
|    y        |   real   |     the y position of the GGL_sub relative to the container  |
|    w        |   real   |     the width of the GGL_sub  |
|    h        |   real   |     the height of the GGL_sub   |

| Returns:  | the GGL_sub created |
|--         |                   --|

Use this method to manually add GGL_sub elements to the container

## Update_logic()
| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|    N/A      |   N/A   |                    N/A                     |

| Returns:  | N/A |
|--         |   --|

This method is called each frame, override it to run your own logic.

# Variable Definitions:

![var_def](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/API/GGL_instance/parent_GGL_container.png)

- **elements_active** => are the elements shown and interactable with?

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Classes.md)
