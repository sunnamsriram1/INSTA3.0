# Instaloader Project

This project uses Instaloader to download Instagram data. It includes functionalities such as handling CSV files, using progress bars with tqdm, and coloring terminal output with colorama.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/sunnamsriram1/INSTA3.0.git
    cd INSTA3.0
    python3 insta3.0_enc.py
    
    ```

2. **Create and activate a virtual environment (optional but recommended):**

    ```sh
    python -m venv venv
    source venv/bin/activate    # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies:**

    ```sh
    pip install -r requirements.txt
  
    ```

## Usage

Run the main script to execute the project. 
import instaloader
import csv
import sys
from tqdm import tqdm
import colorama
from colorama import Fore, Style
import pytz
import datetime
import os

# Your script logic here

```sh
python3 insta3.0_enc.py
