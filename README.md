# ReloadingCalculator
## Introduction
This is a small set of excel based calculators that I use when reloading ammunition. Hopefully this can be of use to someone else.

## Calculators
### OBT (Optimum Barrel Time) Calculator
The is the OBT calculator developed by Johann Yssel at Xpert Bullets using the formula developed by Chris Long (http://www.the-long-family.com/)

### Case Water Capacity Calculator
Input the empty case weight, the water filled case weight. The calculator will determine the water weight of each case and the average water weight of all cases. You can also specify the desired maximum spread and the calculator will determine the most number of cases that fit into that spread and will also highlight them in the table.

### Chrono Speed
Input the measured bullet speeds. The calculator will determine the both the averages with all speeds as well as with the max and min speed removed (Truncated Mean)

### QuickLoad Powder Calibration/Truing
Calculator to help with the calibration of the powder burn rates in QuickLoad. Input the original "ratio of specific heats" and "Burning rate factor". Input a new value for the "Ratio of Specific Heats" and the new value for the "Burning rate factor" is calculated. Input these new values into QuickLoad and see if the adjusted speed matches the measured speed. If not, change the new ratio of specific heats and update the values in QuickLoad until the QuickLoad speed matches the measured speed.
The adjustment should not exceed 3% in either direction.

### VMD Powder Factor
Calculates the required cc for a specified grain of a specified powder.
Supported powders:
* Alliant
* Hodgdon
* Norma
* Somchem
* Vihtavuori
* Western


## Plugin
The Case Water Capacity calculator requires a plugin to be installed for excel. The plugin is available at https://github.com/NemesisXB/Excel-ModeFuzzyUDF/releases
