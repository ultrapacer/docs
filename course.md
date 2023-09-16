This guide will step you through creating a new Course.

#### Getting started

##### Login/Signup

If you do not already have one, create an account on ultraPacer by logging in.
There will be a **"Login/Signup"** link in the top menu if you are not signed
in.

##### Dashboard

Find any courses you've created at the **"Dashboard"** link in the top menu.

##### Create a course

Click on the green **"New Course"** button at the top of the page.

#### New/Modify Course Menu

##### Select a source

###### GPX File

A .gpx file is a file containing latitude, longitude, and elevation points
along the course. These can be downloaded from an actual track recorded, or from
one of various route creation tools.

###### Strava Route

Source the route directly from the Strava Route builder.
Just enter the ID number of the route or the full path,
typically https:\/\/www.strava.com\/routes\/\[*id-number*\], and select "Load"
to import the route into ultraPacer. Updates to the Strava route can later be
carried over to ultraPacer with the Reload button. Note that the route must
be set as "Public" in Strava.

###### Elevation Data

By default, ultraPacer will utilize elevation data from the GPX file (if
present) or Strava Route. Alternatively, elevation can be sourced from Google
or the Elevation API using this selection. If a file was used that does not
contain elevation, the source will default to Google.\
Note that if using Google elevation, elevations may not be exported in GPX
files.

###### Source Stats

This box lists the length/gain/loss statistics of the source(s) used.

##### Name & Description

Type in a name (required) and description (optional).

##### Loop course

If the is multiple loops of the same course loops the same track, you may upload a GPX/route for
a single loop and set the number of loops. Waypoints for the first loop are
repeated on each loop.\
Select **Loop Course** and enter the number of loops.

##### Organized Event

If this course is for an organized event (i.e., a race), select this option to input the start date/time.\
Selecting this option also enables other options later (such as waypoint inputs sepcific to organized events).

###### Date/Time

Date, time, and timezone fields are required for organized events. When later creating plans for a course, a different start date/
time can be selected.

##### Overrides

Optionally, you can override the distance and elevation calculated from the track
file loaded. Use these if you _know_ the course should be a certain distance or
amount of vertical and you believe the input file is incorrect, or if you want a
50k to work out to exactly 50k, for example.\
Note that if using the "Loop course" option below, overrides are for a single
loop.

##### Visible (Public/Searchable/Sharable)

If you intend to share the course with others, this option needs to be enabled.
After which, you can share the course by providing the url to the course and/or
plan.
If Searchable is enabled, the course will be able to appear in search results
from the Search page.

#### Next: Define Waypoints and Terrain

After going through the Create Course menu, the next step is to view the course
and create Waypoint and set Terrain Factors; see the "Create/Modify Waypoints"
section.

#### Modifying a Course

You can later modify any of the settings above for courses you own using the
"Edit" button from the "Dasboard" page or "Actions"->"Modify Course" from the
course page itself.

#### Duplicating a Course

You can create a duplicate of any course you have permission to view using the
"Duplicate Course" option. This is found under the blue "Actions" menu at the
top of the page when viewing the course or race, then going to "Utilities".

#### Reversing a Course

You can reverse any course you have permission to modify using the
"Reverse Course" option. This is found under the blue "Actions" menu at the
top of the page when viewing the course or race, then going to "Utilities".
