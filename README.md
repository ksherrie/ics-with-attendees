ics-with-attendees.js
======================

Note: I don't own any of this. This is just my attempt to add attendees into the mix.

Please refer to the original for more instructions.
https://github.com/nwcell/ics.js


How To Use
----------
Simply use invoke the object and use the functions...

	var cal_single = ics();
	cal_single.addEvent(subject, description, attendee, attendeeemail, location, begin, end);
	cal_single.addEvent(subject, description, attendee, attendeeemail, location, begin, end);
    cal_single.download(filename);


Example
-------
* **[Demo](https://cdn.rawgit.com/ksherrie/ics-with-attendees/7a569e38/demo.html)**


Credits
------------------
* [Travis Krause](https://github.com/nwcell)
* [Kyle Hornberg](https://github.com/khornberg)