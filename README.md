# jquery-mini-event-calendar
A mini calendar with events JQuery plugin.

## How to use

- Download [mini-event-calendar.min.js](/src/mini-event-calendar.min.js?raw=true) and [mini-event-calendar.min.css](/src/mini-event-calendar.min.css?raw=true) 
- Include them in your html
- Copy and paste the code below.

``` javascript
    // TODO: Replace with real events, say from server.
    var db_events = [{
        title: "Board members meeting",
        date: new Date().getTime(),
        link: "events.com/ev2"
    }];

    $(document).ready(function(){
        $("#calendar").MEC({
            calendar_link: "example.com/myCalendar",
            events: db_events
        });
    });
```

You can also use [example.html](/example.html) as a reference point

## Screenshots

Event happening today

![Event today](/screenshots/event-today.png?raw=true "Event today screenshot")

Calendar can be set to start on monday

![Event other day](/screenshots/calendar-starts-monday.png?raw=true "Calendar starts on monday screenshot")