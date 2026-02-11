### INF601 - Advanced Programming in Python
### Jace Hesford
### Mini Project 1

# API Finance Data -> Graph PNGs
## Description
The main goal of this project is to use NumPy, Matplotlib, and yfinance in order to automatically create 5 graphs of stock ticker closing prices across the last 10 trading days, and output it as PNG graph files.

## Getting Started
 
### Dependencies
* No specific OS is required
* See Installing for dependencies
* Main dependencies in requirements.txt
  * yfinance
  * numpy
  * matplotlib
  * +there supporting dependencies
 
### Installing

```
# pull the repository and enter the directory
git clone git@github.com:FloorIsGround/miniproject1JaceHesford.git
cd miniproject1JaceHesford.git

# activate the virtual environment
# on linux/wsl
source .venv/bin/active

# on windows
.venv\Scripts\activate

# create your virtual environment
# For Python
python -m venv .venv
pip install -r requirements.txt

# For uv package manager (what I use)
uv venv
uv pip install -r requirements.txt

```
 
### Executing program
 
* How to run the program
* Step-by-step bullets
```
#python
python main.py

# uv package manager
uv run main.py
```
 
## Authors
 
Jace Hesford
 
## Version History

* 0.1
    * Initial Release
 
## Acknowledgments
 
Inspiration, code snippets, etc.
* [Matplotlib](https://matplotlib.org/stable/api/index.html)
* [yfinance](https://ranaroussi.github.io/yfinance/reference/index.html)
* [NumPy](https://numpy.org/doc/stable/user/absolute_beginners.html)