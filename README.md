# Fermier
An open-source Ferminator clone. Controls temperature inside a fermentation chamber, for beer, cider, wine etc.

The name is a portmanteau of "fermentation" and "peltier". Based on a WEMOS Lolin32 board with Wi-Fi and BT connectivity. Software programmed in Arduino IDE.

## Hardware features:
 * One Peltier element for heating and cooling
 * Two fans, one for circulating air inside chamber and other outside for cooling outside heatsink
 * Three Pt1000 thermistors, one for measuring inside heatsink temperature, one for measuring outside heatsink temperature and one that can be freely placed inside chamber
 * Status LEDs for indicating heating/cooling

## Software features:
 * Control and check status over Wi-Fi
 * PID loop to control chamber temperature

## Suggested external hardware:
 * 1 pc, TEC1-19906 24 volt Peltier element
 * 3 pcs, Pt1000 temperature sensors
 * 2 pcs, 24 volt fan, suitable size for heatsinks
 * 2 pcs, heatsink, dimensions roughly 200 x 50 mm (needs checking)