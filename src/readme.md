# This application is called the Hotel Service and designed for collecting hotel information such as 
# hotel name, hotel features and price per night.

# Main functionality
- Interacting with the application is done through the Command prompt (console). 
- Interaction is achieved using these main action commands, which allow to work with the hotel information in the list:
  - **Add** (information for a new hotel can be added);
  - **View** (information for all hotels in the collection can be viewed)
  - **Search** (detailed info is displayed for a hotel when searched by name)
  - **Delete** (a hotel entry can be removed from the collection/list when the hotel name is provided)
  - **Exit** (exit from the application)

# JUnit
 - Several testing scenarios are set up to test the app functionality:
   - Verify that hotel service is empty when first created
   - The happy path (Test if the "happy path" is working and not throwing exceptions)

# Logging
- Results of the main actions are logged in the logfile.log with the append flag turned on.
