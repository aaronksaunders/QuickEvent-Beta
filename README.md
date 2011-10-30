# quickevent Module

## Description

This Module Allows you to create calendar events in the default user calendar, and displays UI for editing the calendar event

## Accessing the quickevent Module

To access this module from JavaScript, you would do the following:

	var quickevent = require("clearlyinnovative.quickevent");

The quickevent variable is a reference to the Module object.	

## Reference

### quickevent.addEvent

    quickevent.addEvent({
        "dateFormat" : "yyyy/MM/dd hh:mm a", // default format is MMM dd yyyy HH:mm, like  Oct 21 2011 10:00
        "startDate" : "2011/11/01 10:00 am",
        "endDate" : "2011/11/01 10:30 pm",
        //"timeZone" : "EST", // can be specified or used system default
        "location" : "Times Square NYC",
        "title" : "Test Quick Event Title"
    });

## Author

    Aaron K. Saunders
    2011 - Clearly Innovative Inc
    http://blog.clearlyinnovative.com
    twitter:aaronksaunders

## License

SEE ENCLOSED LICENSE
