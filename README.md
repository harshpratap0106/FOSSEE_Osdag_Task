# Osdag Module Unit Testing - Screening Task

This repository contains an automated unit testing suite developed using **PyTest** for the Osdag (Open Steel Design and Graphics) software. The suite verifies the design logic for Cleat Angle, Fin Plate, and Tension Member Welded modules against expected design values.

## 🛠 Setup and Installation

As per the task requirements, follow these steps to set up the environment:

1. **Clone the Osdag Repository:**
   ```bash
   git clone [https://github.com/osdag/Osdag.git](https://github.com/osdag/Osdag.git)

   git clone []
cd [FOSSEE_Osdag_Task]

Install Dependencies: Ensure you have Python 3.x installed, then run:
pip install -r ../Osdag/requirements.txt
pip install pytest pandas openpyxl

Configure Python Path: To allow the tests to access the Osdag modules, add the Osdag directory to your PYTHONPATH:
Bash
# On Linux/Mac:
export PYTHONPATH=$PYTHONPATH:$(pwd)/../Osdag
# On Windows (Cmd):
set PYTHONPATH=%PYTHONPATH%;%cd%\..\Osdag

Running the Tests
To execute the entire test suite and generate a report, run the following command from the root of this repository:
Bash
pytest test_osdag.py -v
