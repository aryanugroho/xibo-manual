<!--toc=scheduling-->
# Events
Events are Layouts or Campaigns assigned to Displays at specific dates and times. The event form can be launched from 
 the Calendar Control buttons and by clicking on any existing event in the calendar.

When launched the form looks like this:

![Scheduling Form](img/scheduling_add_event.png)

## Event Type
Scheduling supports two types of event

 - Campaign/Layout Events
 - Command Events
 
Campaign/Layout events are the main type of event and cause the selected Campaign/Layout to be shown on the Player. Multiple
 items can be scheduled at the same time and they will be shown in a loop according to the Display Order on the event.
 
Command events are executed once per schedule against each display that applies. They can be able [predefined command](displays_commands.html)
 with a command string specified for the Display Settings Profile active on the Display.

## Recurring Events
The scheduler features the ability to create recurring events. To set recurrence for events, select the required 
 "Repeats" value from the list and the appropriate additional fields will be revealed.

A scheduled event can be repeated at defined interval (hourly, daily, weekly, monthly or yearly) until the 
 specified date / time.

## Priority Events
Priority schedules allow an event to be added that overrides all other non-priority events on the schedule. This 
 functionality is useful for displaying temporary important notices, or overriding the schedule for a specific event 
 without having to cancel the layouts that would normally be running at that time.

When adding a new schedule, or when editing an existing schedule, tick the "Priority" box to make the schedule 
 override the others. 

Multiple priority events may be scheduled concurrently. They will be shown in a cycle in the same way as non-priority 
 layouts would be.

## Deleting an Event
To delete an event, first open the Schedule Form and then select the "Delete" button from the button bar on the form. 
 The Delete Event form will open allowing confirmation of the Delete.