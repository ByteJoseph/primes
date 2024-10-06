# Primes (1 to 5 Million)

This repository contains a Python script and a Mojo script that generates prime numbers and stores them in a JSON file, where the **prime number is the key** and its **position in the prime sequence** is the value. This data is particularly useful for cryptographic applications, research, and educational purposes. The current dataset contains all prime numbers between **1 and 5 million**.

### Features
- **Prime Range**: This dataset includes prime numbers from 1 to 5 million.
- **Incremental Prime Generation**: Continuously add new prime numbers without duplicating existing data.
- **Efficient Prime Lookup**: Quickly retrieve prime numbers from a JSON dictionary.

### File Structure
```
./
├── .gitignore        # Standard gitignore to exclude unnecessary files
├── prime.🔥          # Mojo script for generating prime numbers
├── prime.py          # Main Python script for generating prime numbers
├── primes.json       # JSON file containing prime numbers between 1 and 5 million
└── README.md         # Project description and instructions
```

### Usage

#### For Python Script
1. **Run the Python script**:
    ```bash
    python prime.py
    ```
2. **Input a prime limit**: You will be prompted to enter the upper limit of prime number generation.
3. **Generated Output**: The generated primes will be saved in `primes.json` in the format:
    ```json
    {
        "2": 1,
        "3": 2,
        "5": 3,
        "7": 4,
        "11": 5,
        ...
    }
    ```

#### For Mojo Script
1. **Install Mojo** (if not already installed). Follow the instructions on the [Mojo documentation](https://www.modular.com/mojo#:~:text=Mojo%20combines%20the%20usability%20of%20Python%20with%20the%20performance%20of) for installation.
2. **Run the Mojo script**:
    ```bash
    mojo prime.🔥
    ```
3. **Input a prime limit**: You will be prompted to enter the upper limit of prime number generation.
4. **Generated Output**: Similar to the Python script, the generated primes will be saved in `primes.json`.

### Requirements
- Python 3.x
- Mojo (for the Mojo script)

### Contribution
Feel free to contribute by improving the algorithm or expanding the repository with larger sets of prime numbers.
