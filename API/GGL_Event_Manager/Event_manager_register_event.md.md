# Function Event_manager_register_event(_pEvent, _pObjectID, _pScript)

|  Parameter    |  type   |     description        |
|--             |       --|--                      |
|   _pEvent      | string or integer  | the identifier of the event    |
|   _pObjectID      | integer  | the id of the instance registering to the event    |
|   _pScript      | script  | the script that the instance will when the event is fired    |

| Returns:  | true if we want to unregister, false if we keep being resitered |
|--         |                             --|

This function is used to register an instance to an event.

Once the event is fired, the instance resitered with this function will run the script passed as argument.

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Event_Manager.md)
