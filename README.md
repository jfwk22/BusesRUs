## BusesRUs - Term Project

Implemented Android application that, parsing JSON data from [Translink Open API](https://www.translink.ca/about-us/doing-business-with-translink/app-developer-resources), live tracks bus stops itineraries by mapping the location of stops, busses and routes on the Greater Vancouver Transit system. The UI provides a layout of bus stops in the vicinity of the user with the closest stop highlighted for easy of visualization. The user can slide the map display and click on any of the stops to display a list of the busses that pass by the designated stop and provide their arrival/leave times. Bus routes displayed on application each have a unique color to avoid overlapping visual issues.

libs contain JSON, OSMDROID Android (Android emulator) packages

src/ca/ubc/cs/cpsc210/translink contains parsers and project code
