## Class GGL_sub_label

A static GGL_sub which displays a text at it's position and is not interactable with by the user.

## Relevant Methods

## Set_alpha_modifier(value)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   value      | real  |           a real number between 0 and 1     |

| Returns:  | N/A |
|--         |                             --|

Use this method to set a multiplier for "image_alpha"

## Set_label(new_label)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   new_label      | string  |  the new label to display    |

| Returns:  | N/A |
|--         |                             --|

This method let's you set the text to display.

# Variable Declarations:

- **align_h**              => horizontal text alignment
- **align_v**              => vertical text alignment
- **character_separation** => the space between chatacters (calculated automatically, don't touch it)
- **font**                 => the font used by this GUI element
- **label**                => the label displayed
- **carriage_return**      => the maximum string width before a carriage return (calculated automatically, don't touch it)
- **color_label1**         => the color of the label (top)
- **color_label2**         => the color of the label (bottom)
- **color_shadow1**        => the color of the label's shadow (top)
- **color_shadow2**        => the color of the label's shadow (bottom)
- **shadow_label**         => the thickness of the label's shadow (in pixels, scales with the object's scale)
- **offset_label_x**       => horizontal offset from the x position to draw the label
- **offset_label_y**       => vertical offset from the y position to draw the label
- **position_label**       => the position we draw the label at
- **rectangle**            => the bounding box

## [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Struct%20Classes.md)
