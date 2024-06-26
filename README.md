# Acorn Archimedes ARM3 processor card, with FPA.

March 2024


![3D View](Generated/Archimedes_ARM3_FPA_3D_View.PNG)

This is my implementation of an ARM3 upgrade card with FPA that will plug in to the ARM2 socket on early model Acorn Archimedes machines.

The non-FPA version has been tested successfully over a dozen builds using 25MHz and 33MHz parts recovered from dead A5000 machines, and my A540 ARM3 FPA card has been successfully tested in several systems, so this project simply brings those two projects together.

Multiple options are provided for clock source - standard oscillator, SMT oscillator and ICD2053 clock generator.

This design has been built and tested in A3000, running up to a 40MHz Arm3 and FPA11, or 36MHz Arm3 and FPA10.  The THT oscillator and ICD2053 options have been tested and work as expected.  Also tested successfully in A310 and A540 (with my 'ARM2' adapter).


## Licence

No warranty is provided, and this work is used at your own risk.  

Licenced as CC BY-SA 4.0

Copyright 2024 Ian Jeffray

