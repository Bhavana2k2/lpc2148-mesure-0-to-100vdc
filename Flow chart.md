# Flowchart

**1-->Start:**
- This is the starting point of your flowchart.

**2-->Initialize Peripherals:**
- Initialize the microcontroller's ADC and any other necessary peripherals.
- Set up the ADC to measure voltage within the 0-100V range.

**3-->Read ADC Value:**
- Use the ADC to read the voltage value from the sensor or voltage divider connected to the microcontroller.
- Convert the analog value into a digital value.

**4-->Scale ADC Reading:**
- Scale the ADC reading to represent the actual voltage value in the 0-100Vdc range.
- Apply the appropriate scaling factor to convert the digital reading into voltage units (e.g., volts).

**5-->Store Voltage Value:**
- Store the scaled voltage value for further processing or display.

**6-->Process Voltage Value (Optional):**
- If there are any specific actions or processing steps required for the voltage value, include them here.
- For example, you might want to check if the voltage is within a certain range or apply some filtering.

**7-->Output Voltage Value (Optional):**
- If you need to display or communicate the voltage value, include steps to do so.
- This might involve displaying the value on an LCD, sending it over a communication interface (e.g., UART), or using it to control external devices.

**8-->Check for End Condition:**
- Determine whether the measurement process should continue or if it's time to stop and perform cleanup.
- This could be based on a time interval, a certain number of measurements, or a specific event.

**9-->End:**
- This is the endpoint of your flowchart.

**10-->Cleanup (Optional):**
- If there are any resources or peripherals that need to be released or cleaned up, include those steps here.

**11-->Repeat:**
- If the end condition is not met, return to the step of reading the ADC value to continue the measurement loop.
- Create an arrow looping back to the "Read ADC Value" step.

**12-->Stop:**
- If the end condition is met, stop the measurement process and exit the loop.
