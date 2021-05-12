# **Tutorial: setting up your first button using events**

Lets see how to make something simple using a toggle to group / ungroup a couple of other GUI elements.

## **1 - Create the room**:

For the sake of the example, We will create a room with a width of 1280, a height of 720, same for the viewport and window size, then, we drag
a GGL_controller into the room and somewhere in a script file, we create an enum to hold the indexes of the pages of our menu.

![room](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Menus/Menu_room.png)

## **2 - Open the "Creation code of your parent_GGL_menu instance"**:

once the instance is in the room, open the creation code tab and we will declare some variables to simplify our task.

**- Note:**
The coordinates of your GGL_sub elements are relative to the coordinates of the container instances, meaning, the parent_GGL_menu always positions itself at the center of the GUI, so, it's coordinates are the 0, 0 coordinates of the GGL_sub.

Example, if you want a GGL_sub at the center of the GUI, it's coordinates will be x = 0, y = 0

![toggle](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Menus/declarations.png)

## **3 - Create first page of our menu**:

First we will add a group that will contain the 1rst page to the menu by using the "Add_group" method, it takes only a string name as argument.

The method returns the group created, so we can store it into a variable and use this variable to add GUI elements to the group.

We will use the "Add_element" method of the group we created to add some GGL_sub elements to it.

The method takes 7 arguments, and can take an optional 8th argument (which is stored into the "value" variable of the GGL_sub).

Arguments:
- 1 - The type of GGL_sub
- 2 - the label (a string)
- 3 - the script that overrides the "Activate" method
- 4 - the x offset from the position of the menu (middle of the screen)
- 5 - the y offset from the position of the menu (middle of the screen)
- 6 - the width of the GGL_sub
- 7 - the height of the GGL_sub
- 8 - (optional) any kind of variable (goes into the "value variable of the GGL_sub")

![pass_the_func](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Menus/page1.png)

## **4 - **


- **5 - **

![button]()



- **6 - **



![buttons2]()

- **7 - Test your 1rst creation!**



![buttons2]()



