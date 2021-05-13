# **Tutorial: setting up your first button**

Here, you'll learn how to setup an interactive GUI button


## **1 - Create the room**:

Create a room with a width of 1280, a height of 720, same for the viewport and window size, then, drag
a GGL_controller into the room.

![room](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Button/Room.png)


## **2 - Create the button**

Drag a parent_GGL_button into the room, and click on the "variables tab.

Scroll down to the "label", that will be displayed on the button, set the name how you like, i'll go with "My_Button".

![toggle](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Button/button1.png)


## **3 - Create the function that the button will run**:

Somewhere in a script file, write the following function, it will be run by the button, so it can acces all of it's variables, and it so happens that the variable "value" of a button can store anything because it's not used for something specific.

So, we will use the "value" variable of the button to store.. let's say the button number!

Declare a local variable and use the method "Get_value()" to return the "value" variable (learn more about common methods by reading the API). 

Then finally, we'll use the "show_message" function to make use of that local variable.

![page1](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Button/script.png)


## **4 - Attach the script to the button**

Now, go back to your room, scroll down through the variables until you find "Script_Activate", this variable overrides the "Activate" function that's run when the button is clicked.

Pass it the name of the script we created earlier and scroll down to the "value" variable.

pass 1 to "value", as in "button n°1"

![page2](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Button/button2.png)


- **6 - Now is the time to compile and test our creation!**
 
![compile](https://github.com/Ced30/GGL-Documentation/blob/main/Images/Tutorial/Button/Tuto_complete.gif)


# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/README.md)

