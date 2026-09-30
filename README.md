# Digital Logic Circuit Designs

## About the Project

This project contains digital logic circuits developed as part of my **Computer Architecture** studies at the University of Mauritius.

The project focuses on the design and simulation of sequential logic circuits using flip-flops, state diagrams, truth tables, excitation tables, and Karnaugh maps.

Two main circuits were implemented:

1. **1101 Sequence Detector**
2. **Synchronous Counter**

The circuit files can be opened and simulated using **Logisim**.

---

## 1. 1101 Sequence Detector

The first circuit is a sequence detector designed to recognize the binary sequence:

```text
1101
```

The circuit uses **D flip-flops** to store its current state.

It progresses through different states as the sequence is detected and produces an output of `1` when the complete `1101` sequence is recognized.

### States

- `S0` – No valid sequence detected
- `S1` – `1` detected
- `S2` – `11` detected
- `S3` – `110` detected

### Sequence Detector Circuit

![1101 Sequence Detector](https://github.com/Ankush7323/digital-logic-circuit-designs/blob/main/sequence-detector.png?raw=true)

### Sequence Detection

When the complete sequence `1101` is detected, the output becomes:

```text
Y = 1
```

![Sequence Detected](https://github.com/Ankush7323/digital-logic-circuit-designs/blob/main/sequence-detector1.png?raw=true)

---

## 2. Synchronous Counter

The second circuit is a **synchronous counter** implemented using **JK flip-flops**.

All flip-flops use the same clock signal and change state according to the following sequence:

```text
000 → 001 → 011 → 100 → 110 → 000
```

After reaching `110`, the counter returns to `000` and begins a new cycle.

### Synchronous Counter Circuit

![Counter Simulation](https://github.com/Ankush7323/digital-logic-circuit-designs/blob/main/synchronous-counter.png?raw=true)

---

## Design Process

The circuits were designed using:

- State transition diagrams
- Truth tables
- State tables
- Flip-flop excitation tables
- Karnaugh maps (K-maps)
- Boolean expressions
- Logic gates
- D flip-flops
- JK flip-flops
- Circuit simulation

---

## Technologies Used

- Digital Logic
- Logisim
- D Flip-Flops
- JK Flip-Flops
- Karnaugh Maps
- Boolean Logic
- Finite State Machines

---

## Project Files

```text
digital-logic-circuit-designs/
│
├── README.md
│
├── circuits/
│   ├── sequence-detector-1101.circ
│   └── synchronous-counter.circ
│
└── screenshots/
    ├── sequence-detector.png
    ├── sequence-detected.png
    ├── synchronous-counter.png
    └── counter-simulation.png
```

---

## How to Run

1. Install and open **Logisim**.
2. Download or clone this repository.
3. Open one of the `.circ` files from the `circuits` folder.
4. Run the circuit simulation.
5. Toggle the input and clock signals to observe the circuit behaviour.

---

## Academic Project

This project was completed as part of a **Computer Architecture** assignment at the **University of Mauritius**.

It was a group assignment. The repository is intended to showcase the digital logic design and simulation work completed during the module.

## Author

**Suryanshu Bisram**

Computer Science Student  
University of Mauritius
