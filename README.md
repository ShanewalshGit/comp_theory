# Computational Theory Module - 4th Year Software Development

Student ID: G00406694 Name: Shane Walsh

This repository contains the tasks completed as part of the Commputational Theory module in Atlantic Technological University (ATU).

## Tasks Overview
This repository includes solutions to the following computational theory tasks:

### Task 1: Binary Representations
Implementation of four different functions that demonstrate bit manipulation through bit shifts and operations:
- `rotl(x, n=1)`: Rotates bits in a 32-bit unsigned integer to the left
- `rotr(x, n=1)`: Rotates bits in a 32-bit unsigned integer to the right
- `ch(x, y, z)`: Chooses bits from y or z based on whether bits in x are 1 or 0
- `maj(x, y, z)`: Takes a majority vote of bits in x, y, and z

### Task 2: Hash Functions
Implementation of the Kernighan & Ritchie (K&R) hash function converted from C to Python, with analysis of why the use of prime numbers in the algorithm.

### Task 3: SHA256 Padding
Creation of a Python function that calculates the SHA256 padding for a given file according to NIST FIPS 180-4 specifications. This demonstrates the padding scheme that appends:
- A '1' bit
- Enough '0' bits to make the message length a multiple of 512 bits
- The original message length as a 64-bit big-endian integer

### Task 4: Prime Numbers
Implements two different algorithms for the calculation of the first 100 prime numbers, these are:
- Division with square roots
- Sieve algorithm
Both approaches are analyzed for efficiency and correctness.

### Task 5: Roots
Calculation of the first 32 bits of the fractional part of the square roots of the first 100 prime numbers, similar to how the SHA-256 algorithm generates its constants.

### Task 6: Proof of Work
Finding English language words with the greatest number of leading zero bits in their SHA256 hash digests, with some proof of dictionary inclusion.

### Task 7: Turing Machines
Design of a simulation of a Turing Machine in Python that adds 1 to a binary number, complete with state transitions and some examples.

### Task 8: Computational Complexity
Implementation of bubble sort with instrumentation to count comparisons, tested against all permutations of a 5-element list to demonstrate computational complexity principles.

## How to Run This Repository

### Prerequisites
- Visual Studio Code or GitHub Codespaces
- Python and Jupyter Notebook (for running the tasks notebook)
- Required Python packages (install with `pip install -r requirements.txt` if necessary)

### Step-by-Step Instructions

1. **Clone the Repository:**
    ```
    git clone https://github.com/ShanewalshGit/comp_theory.git
    ```

2. **Open in Visual Studio Code:**
    ```
    code .
    ```

3. **Install Required Packages:**
    ```
    pip install -r requirements.txt
    ```

4. **Open the Jupyter Notebook:**
    - In Visual Studio Code, open the tasks.ipynb file.

5. **Run the Notebook:**
    - Ensure you have the Jupyter extension installed in Visual Studio Code.
    - Click on the "Run All" button to execute all cells in the notebook.
    - Note: On first run, the notebook will automatically download the dictionary file needed for Task 6.

6. **View Results:**
    - The notebook will display the results of the various computational theory tasks.

### Running in Github Codespaces

1. **Open Repository in Codespaces:**
    - Navigate to the repository on GitHub.
    - Click on the "Code" button and select "Open with Codespaces".

2. **Follow The Steps Above:**
    - Follow the same steps 3-6 as described above to run the notebook.
    
## Technologies Used

- Python
- Jupyter Notebooks