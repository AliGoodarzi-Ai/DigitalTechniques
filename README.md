# DigitalTechniques
This repository showcases an assembly implementation of a 5-tap Finite Impulse Response (FIR) filter using the mycpu module. It initializes memory with coefficients and input data, executes the FIR algorithm, and validates the output against expected results, confirming the functionality and accuracy of the mycpu module.
# FIR Filter Implementation

## Description
This repository showcases an assembly implementation of a 5-tap Finite Impulse Response (FIR) filter using the `mycpu` module. It initializes memory with coefficients and input data, executes the FIR algorithm, and validates the output against expected results, confirming the functionality and accuracy of the `mycpu` module.

## Overview
The `fir.asm` simulation aims to verify the functionality of the `mycpu` module by executing a program that implements a 5-tap FIR filter. This test involves:

1. **Memory Initialization**: The program sets up memory with predefined coefficients and input data required for the FIR filter calculations.

2. **FIR Filter Calculation**: It performs the FIR filter algorithm using the initialized values, ensuring the correct application of the filter's mathematical principles.

3. **Output Comparison**: The expected output, derived from the filter's algorithm, is compared against the simulation results to verify accuracy.

### Results
The simulation results showed a precise match with the expected outcomes, confirming that the `mycpu` module correctly implements the FIR filter and interacts properly with the memory and I/O ports. Any discrepancies between observed and expected results typically indicate issues in memory initialization or algorithm implementation. However, in this case, no significant differences were noted, validating the correctness of the `mycpu` module's FIR filter functionality.

## Usage
To run the FIR filter simulation, ensure you have the necessary assembly environment set up. Load the `fir.asm` program and follow the execution steps provided in the documentation.

## Contributing
Contributions are welcome! Please open issues or submit pull requests for any improvements or fixes.

## License

