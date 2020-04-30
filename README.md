# Work Day Planner

A simple web-app that incorporates moment.js which allows you to plan your work day in hour-length blocks. You can enter information into a time-block then click the save button to save that information to your local storage. If the current time of day is before a time-block, it will appear green. If it is during a time-block, it will appear white. If it is after a time-block, it will appear red. You can experience the deployed project here: https://jds21171.github.io/Daily-Work-Planner/


## User Story

```
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

## Acceptance Criteria

```
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
```