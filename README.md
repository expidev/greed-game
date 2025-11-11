## Description

Greed is a simple 2D game where the player controls a character that collects the stars "*". 

If you collect a star, you earn a point. If you collide with a square, you lose a point.

## Getting Started

Create and activate a virtual environment

```bash
# Unix / macOS
python -m venv .venv
source .venv/bin/activate

# Windows (PowerShell)
python -m venv .venv
.venv\Scripts\Activate.ps1
```

Upgrade pip and install dependencies

```bash
python -m pip install --upgrade pip setuptools wheel
pip install -r requirements.txt
```

Run the project

```bash
python3 greed
```



## Project Structure
---
The project files and folders are organized as follows:
```python
root                    (project root folder)
+-- rfk                 (source code for game)
  +-- game              (specific game classes)
  +-- __main__.py       (entry point for program)
+-- README.md           (general info)

```
---
## Required Technologies
* Python 3.8.0
* Raylib Python CFFI 3.7
