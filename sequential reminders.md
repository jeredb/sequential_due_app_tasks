# Sequential Due.app Reminders

Using the 'x-callback-url' url scheme, a due reminder can be created for a specified time in future, say 20 minutes.

    due://x-callback-url/add?title=Finish%20Laundry&secslater=1200

Much like the sequential tasks, the sequential reminders can be added to existing alarms and can have multiple reminders embedded.
## Notes

* The note must be % escaped.
* The time unit is seconds, so math is involved. (1200 seconds = 20 minutes)
