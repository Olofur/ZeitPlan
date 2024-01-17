The repository contains .ics files for the zeitplan used in the course
'Tyska i Praktiken/Tyska Intensiv' at Internationella Skolorna Düsseldorf
for the semester spring 2024. Use at your own leasure.

Every file contains one calendar element, which each subsequently holds several
event elements. The important properties of each event are:

	SUMMARY - Main title of the event.
	DESCRIPTION - Description of the event.
	UID - The UID is a unique ID for the event. You can choose these 
	freely.
	DTSTART - Contains the specified time zone for the event followed by
	the date and time of the start of the event of the format 
		YYYYMMDDTHHMMSS
	DTEND - When the event ends. Same time notation as DTSTART.
	LOCATION - Where the event is taking place. For this course almost all
	events are taking place in ISD locales.

A natural follow up of this would be an automation of the Zeitplan management,
maybe through bash piping, sed and input.
