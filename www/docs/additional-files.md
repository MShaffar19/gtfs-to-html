---
id: additional-files
title: Why Additional Files?
---

By default, GTFS-to-HTML attempts to generate a timetable for each  route and direction present in a GTFS file. However, much greater control over which routes, directions and days of the week should be built into timetables is possible by adding some additional, non-standard .txt files to an agencies GTFS.

* [timetables.txt](/docs/timetables) - Specifies which HTML timetables should be built based on route_id, direction_id, days of the week and a date range.
* [timetable_stop_order.txt](/docs/timetable-stop-order) - Specifies the stop order that should be used for timetables.
* [timetable_pages.txt](/docs/timetable-pages) - Specifies which HTML timetables should be grouped together into a single HTML page.
* [stop_attributes.txt](/docs/stop-attributes) - Specifies additional information about a stop.
