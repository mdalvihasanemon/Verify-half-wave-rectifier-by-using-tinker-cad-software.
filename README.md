To verify the operation of a half-wave rectifier using TinkerCAD, you can follow these steps:
 Procedure:
1. Open TinkerCAD: Go to TinkerCAD's circuit simulation feature.
2. Add Components:
   - AC Power Supply: Select an AC voltage source to provide an alternating current input.
   - Diode: Add a diode (preferably a silicon diode like 1N4007) to allow current in only one direction.
   - Load Resistor: Connect a resistor to serve as the load.
   - Oscilloscope: Add an oscilloscope to observe the input and output waveforms.
3. Circuit Connection:
   - Connect the AC power supply to one end of the diode.
   - Connect the other end of the diode to the load resistor.
   - The other terminal of the load resistor should connect back to the power supply, forming a complete circuit.
4. Run the Simulation:
   - Start the simulation and observe the voltage waveform across the load resistor using the oscilloscope.
   - You should see that only the positive half of the AC waveform appears across the load, while the negative half is blocked by the diode.
   
   ![image](https://github.com/user-attachments/assets/fffe2d38-9756-41e8-ac2d-d829ab9adb84)
Expected Output:
In the oscilloscope, you will observe that the output waveform is a pulsating DC, where only the positive half-cycles of the AC input pass through. The negative half is blocked by the diode, confirming the **half-wave rectification**.

 Conclusion:
This simulation confirms the functionality of a half-wave rectifier, which converts an alternating current (AC) signal into a direct current (DC) signal by only allowing the positive half-cycles to pass through.
