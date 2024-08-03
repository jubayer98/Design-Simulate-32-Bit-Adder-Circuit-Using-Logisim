# 32-Bit Adder Circuit Using Logisim

This repository contains the design and simulation of a 32-bit adder circuit using Logisim. The project aims to provide a professional and educational view of designing complex digital circuits.

## Description

A 32-bit adder is a combinational circuit that performs the arithmetic sum of two 32-bit binary numbers. This project uses Logisim, a graphical tool for designing and simulating digital logic circuits, to create a 32-bit adder.

## Tools and Requirements

- **Logisim:** A graphical tool for designing and simulating digital logic circuits.
  - Download and install Logisim from the [official website](http://www.cburch.com/logisim/).

## Features

- **32-Bit Adder Circuit:** A complete design and simulation of a 32-bit adder.
- **Professional View:** The circuit is designed with a clean and professional layout for educational purposes.
- **Modular Design:** The circuit is built using smaller modules for better understanding and scalability.

## Getting Started

### Prerequisites

Ensure you have Logisim installed on your system.

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/jubayer98/Design-Simulate-32-Bit-Adder-Circuit-Using-Logisim.git
   cd Design-Simulate-32-Bit-Adder-Circuit-Using-Logisim
   ```

2. **Open in Logisim:**
   - Launch Logisim.
   - Open the project file (`32-bit Adder Circuit [Jubayer Alam].circ`) in Logisim.

## Usage

1. **Simulation:**
   - Once the project is open in Logisim, start the simulation by clicking on the "Simulate" menu and selecting "Ticks Enabled".
   - Input two 32-bit binary numbers and observe the sum output and carry-out.

2. **Customization:**
   - The modular design allows you to modify and extend the circuit easily.
   - You can add more features or integrate the 32-bit adder into a larger project.

## How It Works

The 32-bit adder circuit is built using multiple 1-bit full adder modules. Each 1-bit full adder takes two input bits and a carry-in bit, producing a sum bit and a carry-out bit. The carry-out from each full adder is connected to the carry-in of the next higher-order full adder.

### Example Configuration

The circuit is organized as follows:

- **Inputs:** Two 32-bit binary numbers (A and B) and a carry-in bit.
- **Outputs:** A 32-bit sum and a carry-out bit.
- **Modules:** 32 instances of 1-bit full adders connected in series.

### Full Adder Module

A full adder is the basic building block of the 32-bit adder. It is designed using basic logic gates (AND, OR, XOR) to perform the addition of two bits and a carry-in.

```plaintext
Inputs: A, B, Cin
Outputs: Sum, Cout

Sum  = A XOR B XOR Cin
Cout = (A AND B) OR (Cin AND (A XOR B))
```

## Contributing

Contributions are welcome! If you have ideas for improvements or new features, feel free to open an issue or submit a pull request.

---

Enjoy designing and simulating your own 32-bit adder circuit with Logisim!
