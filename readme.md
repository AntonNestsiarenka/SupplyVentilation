# SupplyVentilation
Supply ventilation source project based on Owen PLC PR200<br>
### The following features have been implemented:
1. Main algorithm of the supply ventilation system:
 * Fan control in modes: main/spare, switching by operating time;
 * Water heater control: preheating, return water temperature control, freezing protections;
 * Supply air temperature control (PID) with/without return water temperature correction;
 * Season definition;
 * Handling external and internal faults and warnings.
2. Visualization on PLC screen for interaction between program and user:<br>
  * Processing screen transitions, menu access levels, setpoint input/output elements, screen element offsets.<br> *Note: To prevent unskilled intervention in the operation of the system, some sections of the menu are password protected.*
3. Test mode (device control in manual mode for commissioning).<br>
#### *Some functions of the functional blocks are not used in the algorithm, as this was not required for this project. But the development was carried out with the aim of further reuse in other projects with a minimum number of edits and changes.*
