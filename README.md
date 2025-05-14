# Bionic-batteryPCB


Develop a custom PCB for a compact battery module. Only one USB port needed. The Type-C port will be bi-directional. The battery module circuit will power a bionic arm and should be capable to handle load from single motor to upto 7 motors.

A single motor consumes around ~400mA at load. For 7 motors 2.8A of output current is needed.

The circuit will be designed such that it supports multiple capacity batteries from 450mA to 3000mA. The battery charging current should be configurable over I2C. Shunt jumpers should be provided to convey the MCU about the capacity of the battery so that the charging current to be set according to it.

Right now selection of battery according to the dimensions given in the dxf and estimated battery size provided in the picture. The battery should be IEC 62133 certified.
