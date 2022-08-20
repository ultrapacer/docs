This guide will step you through creating and modifying course Waypoints.

#### Getting Started
Make sure you're logged in and viewing the Course you intend to edit.
**You must be the owner/creator of the Course to modify Waypoints.**

#### Select Course Editing View
If not already there, witch to the the **Editing** view using the blue toggle
at the top of the page.

#### Add New Waypoint(s)
Click the **+ New Waypoint** button to create a new Waypoint.
- **Name** is the text shown on the map, chart, and tables
- **Location** is the distance along the Course where it is located
  - This can be fine tuned after adding it (see below)
- **Type** as follows (each has its own color on chart/map):
  - *Aid Station* - resupply location along the Course, with delay set by the
    Plan
  - *Water Source* - feature along the Course with delay set by the Plan
  - *Landmark* - feature along the Course (without delay) notable to show on
    the map or as a segment breakpoint
  - *Junction* - feature along the Course (without delay) often used to
    change Terrain Factors
  - *Other* - miscellaneous feature along the Course (without delay)
- **Visibility** as follows:
  - *Primary* - 1st-level breakpoint in Segments table; always shown on map
    and chart
  - *Secondary* - 2nd-level breakpoint in Segments table; shown on map/chart
    when expanded
  - *Hidden* - never shown; used for modifying Terrain Factors between Major or
    Minor Waypoints
- **Terrain** The Terrain for the Waypoint applies for the segment
  beginning at that Waypoint and going until a different Terrain is set
  later. If left  blank, the Terrain is unchanged from the previous
  Waypoint. Each Terrain Type has a default Terrain Factor, which is is a
  multiplier (increase only) addressing the type of
  surface/trail. If unspecified, Terrain will be inherited from the previous
  Waypoint.
  Typical value ranges by Terrain Type are:
  - Paved: 0%
  - Fireroad: 2-6%
  - Doubletrack: 6-10%
  - Singletrack: 10-15%
  - Technical: 15-25% +

Click **Save Waypoint** when finished

##### Importing waypoints from file
Waypoints can be imported from a .gpx file or a .csv file. This is
iniitiated in the **Editing** view using the upload button
underneath the Waypoints table.

###### Importing waypoints from .GPX file
Waypoints in a .GPX file are included with the **wpt** tag as follows:
```xml
<wpt lat="##.###" lon="##.##"><name>WAYPOINT_NAME</name></wpt>
```

###### Importing waypoints from .CSV file
Waypoints in a .CSV file are included with the rows formatted as below,
where the units of distance are either miles or kilometers based on
your settings.
```csv
WAYPOINT_NAME,LOCATION
```

After selecting either a .GPX or .CSV file, you will be prompted with
the proposed waypoints for import before proceeding.

#### Fine Tuning Waypoints
With **editing: on**, click the row in the table for a Waypoint. An option to
*Adjust Location* is shown in the table. Use the left/right arrows to adjust the
Waypoint up or down the track. Zoom in on the map to see it move along to get it
to just the right location. The step increments for the arrows are:
- **<<<** & **>>>** 1.00 mile (or kilometer if using metric)
- **<<** & **>>** 0.10 mile (or kilometer if using metric)
- **<** & **>** 0.01 mile (or kilometer if using metric)

#### Modifying or Deleting Waypoints
With **editing: on**, Waypoints may be modified or deleted by selecting the
appropriate button in the Waypoints table.

#### Notes
Start and Finish Waypoints cannot be deleted or moved (they are fixed at the
beginning and end of the Course) but they can be renamed. The Terrain Factor of
the Start Waypoint can be modified.

If using a looped course, only the first set of waypoints are shown; these will
be repeated with subsequent loops.
