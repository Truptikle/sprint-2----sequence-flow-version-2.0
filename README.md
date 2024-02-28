# sprint-2----sequence-flow-version-2.0
Sequence Diagram: Calculate Heating Temperature of Water
------------------------------------------------------------------
[Homeowner] -> [Smart Home System]: Gets out of bed
[Smart Home System] -> [Bathroom Geyser]: activateGeyser()
[Bathroom Geyser] -> [Temperature Sensor]: Get current temperature
[Temperature Sensor] -> [Bathroom Geyser]: Current temperature
[Bathroom Geyser]->[HeatingSystem]: Calculate required temperature
[Heating System] --> [Bathroom Geyser]: Required temperature
[Bathroom Geyser] --> [Smart Home System]: Heating temperature
[Smart Home System] --> [Homeowner]: Geyser activate


