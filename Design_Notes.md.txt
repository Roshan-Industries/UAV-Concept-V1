# UAV Concept V1 - Calculations and Design Notes

## 1. Mian Dimensions

|Parameter | Value|
|Wingspan | 1900mm|
|UAV Length, nose to Propellor | 1280 mm|
|Wing chord | 190 mm|
|Maximum fuselage height without antenna/fin | 200 mm|
|Maximum total height | 419.52 mm|
|Total angle | 22.5°|
|Wing reference angle | 6.3|
|Payload mount angle | 60°|

## 2. Aircraft Configuration 

-Fixed-wing UAV concept
-Constant-chord wing
-Rear pusher propeller
-V-tail
-Nose Sensor turret
-Underwing Payload mounts
-Intended role: surveillance/ Reconnaissance UAV concept

## Wing Area Calculation

Formula:
Wing Area = Wingspan x Wing chord
Given:
Wingspan =  1900 mm
Wing Chord =190 mm
Wing Area = 1900 x 190 mm
Wing Area = 361000 mm^2
Convert to m^2

Wing Area = 0.361 m^2

## Aspect Ratio Calculation 

Formula:
Aspect ratio + Wingspan^2 / Wing Area
Using meters:
Wingspan = 1.9m
Wing Area = 0.361 m^2
Aspect Ratio = (1.9 x 1.9)/0.361
Aspect Ratio = 3.61/0.361

Aspect Ratio == 10 -------------------------> { Aircraft Type| Aspect Ratio}
						Fighter Jet  | 2-4
						General Aviation | 6-8
						UAV/Reaper Type | 10-15
						Glider | 20-30		}
Aircraft Type:- Long-endurance UAV

## Notes on propellor Size

The Current CAD propellor radius IS 7.7 mm, giving a diameter of 15.4mm. This is not realistic for a UAV with a 1900 mm wingspan
The Value should be treated as a visual CAD placeholder only.
Real propellor diameter = TBD after motor selection.

## Design Interpretation 
The aspect ratio of approximately 10 indicates a long and narrow wing configuration.

This is suitable for:
-Better lift-to-drag ratio
-Efficient Cruise flight
-Surveillance missions 
-Endurance-Oriented UAV design 
This is less suitable for:
-High-Speed maneuvering 
-Aggressive aerobatics 
-Heavy payload missions without structural reinforcement.
