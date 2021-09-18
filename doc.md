

# Description:

- Holiday-Calendar-Plugin;
 helps you and your team to stay organized with a shared calendar. From viewing your company monthly events in one screen to receiving up-to-the-minute reminders, the company holiday calendar has everything you need to create and manage events.

# create-event
    creates a new event given a request body of required key-value pairs. Returns ID of a created event.

## Request Body schema: application/json

## Parameters
|   Name                |   Data type
---------------------------------------
 	Event title         |   string
 	Start and end date  |   string
 	Start  and end time |   string
 	Time zone           |   string
 	Description         |   string
 	All day             |   Boolean
    Event tag           |   string
 	Event color         |   string
 	Reminder            |   string


## Url link
- https://calendar.zuri.chat/api/v1/create-event/

Note: there is a need for authentication. the response is in JSON format.


## Response
```s h
201
```- The resource is successfully created.


## how to create an event
- Click on Add Event
- Enter event title
- Enter start date
- Enter end date
- Enter start time
- Enter end time
- Select time zone
- All day, True or False
- Enter event tag
- Select event color
- Set reminder date and time

## The endpoint is setup using django REST framework