# Function Event_manager_fire_event(_pEvent)

|  Parameter    |  type   |     description        |
|--             |       --|--                      |
|   _pEvent      | string or integer  | the identifier of the event    |

| Returns:  | true if we want to unregister, false if we keep being resitered |
|--         |                             --|

This function is used to fire an event, run it and all the instance subscribed to this event will run their associated functions.

Once the event is fired, the instance resitered with this function will run the script passed as argument.

# [Back](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Event_Manager_Functions.md)

