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

Sequence diagram consists of homeowner which is linked with smart home system,which inturn connected to bathroom geyser that means if owner is connected to smart system the bathroom geyser turns on.and also includes more complexity, no safety measures are taken hence we need to consider some safety mesure to control the geyser.
Sprint-1 consists some of the commits where we need to add the safety measures.


