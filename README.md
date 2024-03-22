# Work-Scheduler
About this Challenge: simple calendar application that allows a user to save events for each hour of a typical working day (9am–5pm).

User Story: 
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively

Acceptance Criteria: 
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with time blocks for standard business hours of 9am to 5pm
WHEN I view the time blocks for that day
THEN each time block is color-coded to indicate whether it is in the past, present, or future
WHEN I click into a time block
THEN I can enter an event
WHEN I click the save button for that time block
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist

Notes:
Received support from tutor on adding a listener for click events on the save button (line 4-17 in script.js), adding code to get any user input that was saved in localStorage and set(line 32-37 in script.js), and adding code to display the current date in the header of the page (line 48-49 in script.js)

Utilized the Xpert learning assistant to figure out how to add code to apply the past, present, or future class to each time block by comparing the id to the current hour

