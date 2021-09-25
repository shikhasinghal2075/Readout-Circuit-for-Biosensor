# Readout-Circuit-for-Biosensor
Arduino based readout circuit for biosensor.

A biosensor is an analytical device (used for the detection of analyte) incorporating a biological sensing element either intimately connected to or
integrated within a transducer. It basically converts a biological response into an electrical signal.
-When the sample strip is applied to the Read-Out circuit or biosensor, it completes the circuit.
- As a result there is flow of current through the sample resistance and circuit.
-The op-amp or the trans-amplifier converts the current flowing into corresponding voltage signal at the output of amplifier.
-The output of amplifier is fed to the micro-controller through external 16-Bit ADC where the calculations are done and the value of sample resistance is calculated.
- Based on the calculated value of micro-controller, biosensor detects the level of ailment in the body by comparing it with some reference value and
displays on a LCD
