# EAS(Y) 440 mini pinout

The EAS(Y) 440 mini's motor driver is connected with a DB25 connector.
The pinout is from the official documentation by EAS.

DB25 Pin | Function | Direction
------------ | ------------- | ------
1   | Relay 1 (Spindle)     | Output
2   | Direction X           | Output
3   | Step X (X2)           | Output
4   | Direction Y           | Output
5   | Step Y                | Output
6   | Direction Z           | Output
7   | Step Z (TODO: CHECK)  | Output
8   | Relay 3               | Output
9   | Relay 4               | Output
10  | Endswitch X           | Input
11  | Endswitch Y           | Input
12  | Endswitch Z           | Input
13  | Endswitch X2 && Length Sensor | Input
14  | Relay 2 (Pump)        | Output
15  | Endswitch A           | Input
16  | Direction A           | Output
17  | Current Reduction     | Output
18  | Step A                | Output
19  | Input 7               | Input
20  | Step X2               | Output
21  | Hoodswitch            | Input
22  | NC                    | NC
23  | NC                    | NC
24  | NC                    | NC
25  | GND                   | PWR
