# **Tutorial: setting up your first group**

Lets see how to make something simple using a toggle to group / ungroup a couple of other GUI elements.

## **1 - Create the room**:

For the sake of the example, We will create a room with a width of 1280, a height of 720, same for the viewport and window size, then, we drag
a GGL_controller into the room and somewhere in a script file, we create an enum to hold the indexes of the pages of our menu.

![room](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Menus/Menu_room.png)

## **2 - Open the "Creation code" tab of your parent_GGL_menu instance**:

once the instance is in the room, open the creation code tab and we will declare some variables to simplify our task.

**- Note:**
The coordinates of your GGL_sub elements are relative to the coordinates of the container instances, meaning, the parent_GGL_menu always positions itself at the center of the GUI, so, it's coordinates are the 0, 0 coordinates of the GGL_sub.

Example, if you want a GGL_sub at the center of the GUI, it's coordinates will be x = 0, y = 0

![toggle](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Menus/declarations.png)

## **3 - Create first page of our menu**:

First we will add a group that will contain the 1rst page to the menu by using the "Add_group" method, it takes only a string name as argument.

The method returns the group created, so we can store it into a variable and use this variable to populate the group, using it's "Add_element" method.

The method takes 7 arguments, and can take an optional 8th argument.

Arguments:
- 1 - The type of GGL_sub
- 2 - the label (a string)
- 3 - the script that overrides the "Activate" method (pass -1 if you don't want to pass a script)
- 4 - the x offset from the position of the menu (middle of the screen)
- 5 - the y offset from the position of the menu (middle of the screen)
- 6 - the width of the GGL_sub
- 7 - the height of the GGL_sub
- 8 - (optional) any kind of variable (goes into the "value variable of the GGL_sub")

In this example, we will use the 8th argument to pass the enum entry corresponding to the 2nd page of the menu to the "Options" button, and we will pass the "GGL_script_menu_set_group" function to this button.

This function will read the "value" variable of the GGL_sub running it and use it as index to switch to another menu group (page).

The GGL_sub we don't use in this example will receive -1 as 3rd argument (script).

And finally, we will pas as script that closes the game once the click sound has finished playing to the "Quit" button.

![page1](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Menus/page1.png)

## **4 - Create the second page**

The first button, "sound", will lead to the 3rd page of the menu, so, we pass the index of the 3rd page as 8th argument and we pass the function to change menu group.

2nd and 3rd elements are for show only, they are toggles, and they receive -1 as script argument.

The las button leads back to page1.

![page2](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Menus/page2.png)

- **5 - Create the last page**

Finally, we create the 3rd and last group of this menus, it contains 3 sliders that are just here for show purposes.

Just because i'm french, we will set their respective colors to the colors of the french flag, and we will create a last button, leading back to page2

![page3](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Menus/page3.png)

- **6 - Now is the time to compile and test our creation!**
 
![compile](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Menus/Tuto2_complete.gif)


# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/README.md)
