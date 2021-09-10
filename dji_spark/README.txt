This folder contains the datasets for the DJI Spark drone taken with
the Ancortek 5.8GHz radar. A picture of the drone is included in
the folder.

Dataset Description
===================
r1, r2 refer to Receiver 1 and Receiver 2, respectively.

'vary' and 'const': the drone was strapped stationary to a stand
while the blades were spun at their idle speed (const) and when they
were given varying amounts of acceleration (vary).

'hover_Xm' : the drone is hovering X meters in front of the radar.

'forwardback_Xm' : the drone starts X meters away from the radar and is
flown towards and away from the radar about 1 meter either way.

'side_Xm' : the drone starts X meters in front of the radar and moves
left-right w.r.t. the radar, 1 meter either way.

'updown_Xm' : the drone starts X meters in front of the radar and moves
up-down w.r.t. the radar, about 1 meter either way.

The distance X meters is the actual distance i.e. measured using a tape
measure.

File name     | Range bin with target | Actual distance
----------------------------------------------------
dji_1m_vary   | 7 		      | 1m
dji_2m_vary   | 10 		      | 2m
dji_4m_vary   | 17 		      | 4m
dji_6m_vary   | 24 		      | 6m
dji_8m_vary   | 31 		      | 8m
dji_10m_vary  | 40 * 		      | 10m

File name      | Range bin with target | Actual distance
----------------------------------------------------
dji_1m_const   | 7 		       | 1m
dji_2m_const   | 10 		       | 2m
dji_4m_const   | 17 		       | 4m
dji_6m_const   | 24 		       | 6m
dji_8m_const   | 31 		       | 8m
dji_10m_const  | 40 * 		       | 10m

* : extremely faint, barely visible.