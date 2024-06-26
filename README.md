# Quantum Simulator

Completed as part of the FRI (Freshman Research Initiative) at UT Austin.

### Warning

Code contains `eval()` methods, so be careful of what files you choose to read.

### Setup

1. Download or clone repository
    ```
    git clone https://github.com/Mezwer/Quantum-Simulator.git
    ```

2. Install Python libraries
    ```
    pip install matplotlib
    pip install numpy
    pip install notebook
    ```

    or 

    ```
    pip install -r reqs.txt
    ```

3. Download or make your own QASM file (can just be a plain .txt file that looks like a QASM file), and put it in `pyfiles`, or change file paths in code as needed.

### Files

Python files in `pyfiles` can be modified, and the `quantum_circuit.ipynb` file contains a breakdown of the code and techniques used in the program. 

Documentation in code.

### Running the Program

    jupyter notebook quantum_circuit.ipynb

or on Mac,

    python3 -m notebook quantum_circuit.ipynb

### Note

The quantum circuit computed by the program when first opened (results of computation in the graphs at the end of the `quantum_circuit.ipynb` file) is

![alt text](readme_files/image.png)