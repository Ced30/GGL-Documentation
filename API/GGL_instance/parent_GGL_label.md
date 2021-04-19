# Class parent_GGL_label

This class displays a label at it's position and is not interactable with by the user.

# Relevant Methods

## Draw_text_at(text, x, y, color1, color2)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   text      | string  |           the text to draw                 |
|   x         | real    |      the x position to draw the text at    |
|   y         | real    |       the y position to draw the text at   |
|   color1    | color   |       the text color (top)                 |
|   color2    | color   |        the text color (bottom)              |

| Returns:  | N/A |
|--         |                             --|

Draws text at a given location, and a given color.

## Set_alpha_modifier(value)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   value      | real  |           a real number between 0 and 1     |

| Returns:  | N/A |
|--         |                             --|

Use this method to modify or limit the alpha value af the whole instance draw event

## Set_label(new_label)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   new_label      | string  |  the new label to display    |

| Returns:  | N/A |
|--         |                             --|

This method let's you set the text to display.

# Variable Definitions:

![var_def](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/API/GGL_instance/parent_GGL_label.png)

- **font**                => the font used by this GUI element

- **label**               => the label displayed

- **align_h**             => horizontal text alignment

- **align_v**             => vertical text alignment

- **color_label1**        => the label's top color

- **color_label1**        => the label's bottom color

- **color_shadow1**       => the shadow's top color

- **color_shadow1**       => the shadow's bottom color (in pixels, and scales with the object's scale)

- **offset_label_x**      => horizontal offset from the x position to draw the label

- **offset_label_y**      => vertical offset from the y position to draw the label	

- **shadow_label**        => the thickness of the shadow behind the label

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Classes.md)
