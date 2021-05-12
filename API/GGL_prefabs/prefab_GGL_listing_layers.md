## Class prefab_GGL_listing_layers

This prefab is intended to be used to list layer names.
		the "parameters" variable must contain an array of strings
		which represent the names of the layers.
	
Override the specific scripts to implement your logic,
		see the "variables" tab after placing the instance in the room.
	
The prefab comes preloaded with: 
- 1 slider to navigate through the file names									   
- 1 button to add a new name, linked to the "Add_entry"    method									 
- 1 button to delete a name,  linked to the "Remove_entry" method										 
- 1 button to toggle layer visibility,  linked to the "Set_layer_visible" method									 
- 1 up button with the value of -1, to switch the file with the file above. this button is linked to the "Switch_indexes" method									   
- 1 down button with the value of 1, to switch the file with the  file below. this button is linked to the "Switch_indexes" method
- 1 text input box, which is linked to the "Rename_entry" method
									 
The array of strings is drawn on a surface, which is partially hidden with a mask, to scroll through 
		the array, you can either :  - use the slider
									 - use the mouse wheel
								
To select an entry, just click on it

## Relevant Methods

## Activate()

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   N/A      | N/A  |  N/A    |

| Returns:  | N/A |
|--         |                             --|

Override this method with the "activate_override" variable in the variable definitions tab to run your own functions when the button is clicked.

## Set_new_listing(pStringArray)

| Parameter   |  type   |              description                   |
|--           |       --|--                                          |
|   pStringArray      | an array of strings  |  array of strings containing the new listing    |

| Returns:  | N/A |
|--         |                             --|

Use this method to update the listing of strings you wanna display by providing a new array of strings

# Variable Definitions:

![var_def](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/API/GGL_instance/prefab_GGL_listing_layers.png)


- "Script_set_layer_visible" => the script that you must override to implement your own logic when the "visible" button is toggled.

## [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Prefabs.md)

