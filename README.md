# Nine

## Setup Instructions

1. Clone this repository.

2. Create a virtual environment. You may do this using `python -m venv /path/to/new/virtual/environment`. For an easier solution, open the project in VSCode, open the `requirements.txt` file, and click on the 'Create Environment...' button, making sure to select the `requirments.txt` file when prompted to select dependencies to install. At present, use [Python 3.11.3](https://www.python.org/downloads/release/python-3113/).

3. If you are missing dependencies, run `venv\Scripts\activate.bat` (or the appropriate script for your chosen shell) then `pip install -r requirements.txt` to install them.

### Command Line Instructions

After installing [Python 3.11.3](https://www.python.org/downloads/release/python-3113/) (check with `python --version`), run the following commands:

```shell
git clone https://github.com/TenMinusOne/Nine
cd Nine
python -m venv venv
.\.venv\Scripts\activate.bat
pip install -r requirements.txt
```