ics-with-attendees

Atttempting to add attendees into the mix. Note: I don't own any of this. 


How To Use
----------
Simply use invoke the object and use the functions...

	var cal_single = ics();
	cal_single.addEvent(subject, description, attendee, attendeeemail, location, begin, end);
	cal_single.addEvent(subject, description, attendee, attendeeemail, location, begin, end); // yes, you can have multiple events :-)
    cal_single.download(filename);


Credits
------------------
* [Travis Krause](https://github.com/nwcell): Me
* [Kyle Hornberg](https://github.com/khornberg): Added multi event functionality and made everything a package firendly