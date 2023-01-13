Check the full list of changes in scheduler at https://docs.webix.com/scheduler__whats_new.html

## Version 9.0.2 (October 2021)

### Fixes

- regression: date cannot be changed via small calendar and in month mode in compact

## Version 9.0 (October 2021)

### Fixes

- Overriding default views and serviced doesn't always work for Windows builds
- Timeline view: incorrect drag-n-drop of recurring events
- Dragging a recurring event as 'this' makes further editing as 'this' work incorrectly
- Timeline view: dragged item shows in front of all UI elements and overflows the chart
- Currently selected event is not visible or not selected after dates or recurring pattern are changed in the form
- Timeline view: vertical scroll does not work properly on smaller screens
- Timeline and Unit Views: impossible to alter specific occurrences of recurring events
- Month view in IE does not render grid and events after mode change
- export to PNG and PDF as image
- Timeline view: webix.Date.startOnMonday is mishandled
- adding custom fields to Form requires less customization
- adjusting tab width to current locale in localization samples

## Version 8.3 (April 2021)

## Major Features

- Timeline view
- Units view
- Fixes for recurring events and dynamic loading

## Version 8.2 (March 2021)

### Fixes

- NodeJS backend: long events and recurring events get multiplied on client with dynamic loading
- dynamic loading misses recurring events if start date is earlier than 'from' date
- incorrect recurring pattern due to incorrect processing of form values
- recurring form: switching between monthly and yearly patterns does not refresh options
- adding new events is possible via double clicks in readonly mode
- multi-day event length is calculated incorrectly
- changing time of all occurrences of recurring events results in the change of start date and recurring pattern
- limiting tabs: incorrect customization logic
- turning off compact mode results in an error
- menu for deleting repeated events becomes inactive after cancelling

## Version 8.1 (December 2020)

### Major features

- Ability to load and save UTC dates from server

## Version 8.0 (October 2020)

### Major features

- Four display modes: day, week, month, agenda
- Preview and editing of events in the side panel
- Events Drag-n-drop
- Ability to group events into calendars
- Support for recurring events
- Optional Readonly mode
- Desktop and compact layouts
- 5 skins: Material, Mini, Flat, Compact, Contrast
- Golang and NodeJS backend
