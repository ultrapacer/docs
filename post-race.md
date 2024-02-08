This guide will step you through comparing your actual race performance to
an ultraPacer plan.

#### Getting Started

1. You will need to have downloaded the .gpx file for your activity. This can be
   done from any fitness tracking platform (Strava, Garmin, etc).
2. Make sure you're viewing the Course and have selected the plan you would like
   to compare.

#### Post-Race View

If the date of your race has past, you will see a selection menu at the top of
the page that includes "Post-Race" view. Otherwise you can get to the comparison
feature under the Actions menu.

#### Compare to Activity

Click Browse to select your .gpx file, then select Load to process it. The tool
will map time from your activity to the points and aid stations in the Course on
ultraPacer.

#### Viewing Results

On the profile graph, you will see your time ahead/behind your plan, with
positive values on the right axis being ahead (faster than) your plan.
![ultraPacer Activity Comparison](./img/courseCompareGraph.png)

The Segments and Waypoints tables will now have green columns showing your
actual activity data.
On the Segments table, there is a column for actual Elapsed Time that can be
compared to your planned Elapsed Time at each segment.
On the Waypoints tab, you will see actual Arrival and Delay times for each
waypoint.

##### Actual Delay

An estimate of your **Actual Delay** at each waypoint/aid station is shown in the Plan table. This estimate is provided by evaluating a point on the course 200m before and 200m after the aid station location. ultraPacer knows from the modeling how long it _should_ have taken you to cover that distance without the aid station, and that is compared it to how long it _actually_ took to do to. The **Actual Delay** is the difference. It is not just an estimate of "time not moving", but rather the total time cost of the aid station, and is intended to envelope movement around the aid station (eg between tables and bathrooms and drop bags), slow down while packing up on the way out, etc.
