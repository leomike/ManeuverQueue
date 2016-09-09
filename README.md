# ManeuverQueue

ManeuverQueue is an add on for Kerbal Space Program that allows you to sort and filter objects displayed in the Tracking Station list. It was developed and tested against KSP v1.1.3

## Installation

You can build from source or download here [https://github.com/FatHand/ManeuverQueue/releases] (https://github.com/FatHand/ManeuverQueue/releases). Add the contents of the archive to your KSP GameData folder. 

## Usage

When the add on is installed you will see a small toolbar at the top left of the Tracking Station. Switching modes will sort and filter the list in the tracking station. All vessel type filters apply normally.

MET

- Shows the default Tracking Station list

MNV

- Shows only those ships with maneuvers nodes
- Sorts ships by maneuver node time, earliest first
- Ships with maneuver node times in the past will appear at the top of the list
- A ship is only listed once even if it has multiple maneuver nodes
- Color coding
  - Yellow
    - Two ships' next maneuver nodes are less than 15m apart
    - A ship's next maneuver node is less than 15m away
  - Red
    - The ship's next maneuver node is in the past

A-Z

- Shows the default list, sorted alphabetically

## Known Issues

- Certain tracking station operations such as untracking an object, terminating a vessel, or switching vessel filters causes the list to flicker momentarily

## Bugs and Feature Requests

Feel free to submit issues or feature requests here or on the KSP forums [http://forum.kerbalspaceprogram.com/index.php?/topic/146568-113-maneuverqueue-v01/] (http://forum.kerbalspaceprogram.com/index.php?/topic/146568-113-maneuverqueue-v01/)
