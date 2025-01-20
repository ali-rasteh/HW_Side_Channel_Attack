# HW_Side_Channel_Attack

# Side-Channel and Fault Injection Attacks on Cryptographic Algorithms

This repository contains the work for **Hardware Security: Side-Channel and Fault Injection Attacks**, which focuses on demonstrating and analyzing hardware vulnerabilities in cryptographic algorithms through side-channel attacks and fault injection methods. The project consists of two main parts: a Differential Fault Attack (DFA) on DES and a Correlation Power Analysis (CPA) attack on AES.

## Project Description

### Overview
Side-channel attacks and fault injection techniques are critical topics in hardware security, exposing vulnerabilities in cryptographic implementations. This project aims to:

1. **Part 1: DES Fault Attack**  
   Develop a Jupyter Notebook simulating a Differential Fault Attack (DFA) on the DES encryption algorithm. This involves injecting faults in the 15th round of DES, analyzing the resulting ciphertexts, and deriving the original key.

2. **Part 2: AES Power Channel Analysis**  
   Conduct a real-world Correlation Power Analysis (CPA) attack on AES encryption using the ChipWhisperer Nano hardware. This includes setting up the ChipWhisperer environment, analyzing power traces, and retrieving the AES key.

---

## Repository Contents

### 1. Jupyter Notebooks
- **DES Fault Attack Notebook**:  
  A detailed notebook simulating a DFA on DES. It includes:
  - Code to inject faults in the 15th round.
  - Procedures to derive the round key and reconstruct the original key.
  - Explanatory comments and diagrams walking users through the process.

- **AES CPA Notebook**:  
  A notebook designed for use with the ChipWhisperer Nano to execute a CPA attack on AES. It demonstrates:
  - Setting up the hardware and environment.
  - Using power traces to retrieve the AES key.
  - Customization options for the key and attack parameters.

### 2. Documentation
- **Setup Guide**:  
  Detailed instructions for installing the required environments:
  - Setting up the ChipWhisperer development environment.
  - Running the CPA attack.

- **Methodology & Explanation**:  
  Provides an explanation of the fault injection attack on DES and the CPA attack on AES. Diagrams and step-by-step walkthroughs are included.

### 3. Deliverables
- **Jupyter Notebooks**:  
  Finalized notebooks for Part 1 and Part 2.
- **Explanatory Video**:  
  A short video showcasing:
  - The ChipWhisperer setup and its role in the CPA attack.
  - Execution of the CPA attack, including the retrieval of the correct AES key.

---

## Getting Started

### Prerequisites
- Python (Version 3.7 or above)
- Jupyter Notebook
- ChipWhisperer Nano hardware

### Installation
1. **Set up ChipWhisperer environment**:
   Follow the official [ChipWhisperer installation guide](https://chipwhisperer.readthedocs.io/en/latest/index.html#installation).
2. **Clone this repository**:
   ```bash
   git clone https://github.com/yourusername/hardware-security-hw4.git
   ```
3. **Install dependencies**:
   Navigate to the repository directory and install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
1. Open the Jupyter notebooks:
   ```bash
   jupyter notebook
   ```
2. Run the `DES_Fault_Attack.ipynb` for Part 1.
3. Set up and execute the `AES_CPA_Attack.ipynb` for Part 2.

---

## Deliverables
- **Notebooks**:
  - `DES_Fault_Attack.ipynb`
  - `AES_CPA_Attack.ipynb`
- **Video Explanation**

---

## Contributors
- Ali Rasteh
- NYU Tandon School of Engineering  
