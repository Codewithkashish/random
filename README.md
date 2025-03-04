# random


# Random Text Generator

## Overview
This is a simple Python script that generates a random 6-character text string using a combination of uppercase letters, lowercase letters, and digits.

## Features
- Generates a random text string of 6 characters.
- Uses a combination of letters (A-Z, a-z) and digits (0-9).
- Simple and lightweight.

## Requirements
- Python 3.x

## Installation
No external dependencies are required. Just make sure you have Python installed on your system.

## Usage
1. Copy the script below and save it as `random_text_generator.py`.
2. Run the script using Python:
   ```sh
   python random_text_generator.py
   ```
3. It will generate and print a random 6-character string.

## Code
```python
import random
import string

def generate_random_text(length=6):
    return ''.join(random.choices(string.ascii_letters + string.digits, k=length))

random_text = generate_random_text()
print("Random Text:", random_text)
```

## License
This project is open-source and free to use.

## Author
[Your Name]

