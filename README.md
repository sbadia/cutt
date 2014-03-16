cutt
====

the mutt of Calendaring ;)  <- that's the long-term goal


cutt aims at providing a simple command-line interface (possibly curses, in
the future) to manipulate CalDav calendars.

Using it
--------
1. Create a ~/.cutt.json file. Example:
	{
	  "calendars": {
	    "calendar1": {
	      "uri": "https://zimbra.organization.fr/dav/jdoe/Calendar",
	      "user": "jdoe",
	      "password": "Bie5hoot"
	    },
	    "radicale": {
	      "uri": "http://myhomeserver.altu.net/radicale/user/calendar.ics",
	      "user": "user",
	      "password": "seJ0eem8"
	    }
	  }
	}

2. Run 'cutt' (that's pretty much everything that works currently).

Goals for version 1.0
---------------------
- ability to list the next events in several calendars
- ability to add events

Contributing
------------
You need:
- Ruby
- the agcaldav library
Debian packages for agcaldav and its dependencies are available
at http://blop.info/p/20140316-cutt-devkit.tgz (proper Debian
packages are on the TO-DO list)
