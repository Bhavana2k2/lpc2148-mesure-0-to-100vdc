### Step 1: Determine the ADC Resolution in Voltage Steps (LSB)

-The Voltage per LSB (V_LSB) is calculated as:V_LSB = Vref / (2^N)

-In this case, with a 100V reference voltage and a 10-bit ADC (N=10):V_LSB = 100V / (2^10) = 0.0977V (approximately 97.7mV)

### Step 2: Calculate the Theoretical Accuracy

-Theoretical Accuracy is calculated as half of the Voltage per LSB:

V_LSB / 2   
-Using this formula, we divide V_LSB by 2 because, theoretically, the ADC can produce a reading anywhere within the range of +/- 0.5 LSB with equal probability. This is how we calculate the worst-case accuracy:

Theoretical Accuracy = (0.0977V / 2) = 0.04885V or approximately 48.85mV

