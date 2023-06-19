# Alpha Red Hat Automation
### _Automation tool able to create Red Hat Effective License Position reports based on simple input files_

Alpha Red Hat Automation is a python script able to read and write ms excel files using python_openpyxl

## Features
- Graphical User Interface for a better user experience
- Input Microsoft Excel file as a data report (.xslx)
- Generate Excel template with all calculations done 

## Tech

Alpha Red Hat Automation uses a number of open source projects to work properly:

- [Python](https://www.python.org/) - Python for the programming language
- [OpenPyXl](https://openpyxl.readthedocs.io/en/stable/) - OpenPyXl as the main package for reading/writing excel files
- [Tkinter](https://docs.python.org/3/library/tkinter.html) - Tkinter used for the GUI

## Installation

Alpha Red Hat Automation requires [Python](https://www.python.org/) v3.0 or above to run

Install the dependencies and start the program

Open your command prompt and go to your project folder
and install the latest version of OpenPyXl
```sh
python get-pip.py
pip install openpyxl
```
(Optional) If you're using Anaconda prompt

```sh
conda install openpyxl
```
## Running the program

If all dependencies have been downloaded, you may go to the root folder of your project
```sh
example: cd C:\Users\jeoverweg\VsCodeProjects\AutomationExcel
```

You may run the script be it on command prompt or Anaconda prompt
```sh
py main.py
```
If all goes well you'll see a new window pop-up, it's our Alpha Red Hat Automation program.

## Thoughts

Be careful when adding a data report, the template has to be exactly the same otherwise it won't work properly

## Documentation

The program has been commented and docstrings have been added for all functions
You may generate Markdowns thanks to Sphinx or other open-source projects on GitHub

## License

MIT
