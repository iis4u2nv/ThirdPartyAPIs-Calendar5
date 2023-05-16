# Third-Party APIs-Calendar5: Work Day Scheduler

## Task

I created a simple calendar application that allows a user to save events for each hour of the day. It runs in the browser and features dynamically updated HTML and CSS powered by jQuery.

I used the [Day.js](https://day.js.org/en/) library to work with date and time.

## User Story

```md
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

## Acceptance Criteria

```md
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

The following animation demonstrates the application functionality:

![A user clicks on slots on the color-coded calendar and edits the events.](./Assets/05-third-party-apis-homework-demo.gif)

## Operation

This workday calendar displays work hours of a day from 8AM - 5PM.
On the top of the page, current day and date are diplayed.
Each time block is color coded to indicate whether it occurs in the past(gray), present(red), or future(green).
Each time block has an input field and save button where users can store their schedule.
Once it saved, it will store in their local storage.
This calendar is desktop and mobile compatible.

## Contributor

Amazing Grace ©2023 All Rights Reserved.
