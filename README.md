# sequntial-batch-mixing-two-liquid-plc
Automated Sequential Batch Mixing System using EcoStruxure Machine Expert, and AVEVA Plant SCADA


## Key Technical Execution
**PLC Control Logic:** 
* Developed a 27-rung EcoStruxure program from scratch to automate temperature scaling, mixing stages, and production cycle counts.

**SCADA Integration:** 
* Bridged the PLC and AVEVA Plant SCADA using Modbus TCP/IP to give a clear, real-time view of tank levels and temperatures.

**Safety & Alarms:** 
* Added multi-condition fault handling that triggers visual alarms and logs history if temperature or tank levels go out of bounds, with a manual reset button for safe recovery.
