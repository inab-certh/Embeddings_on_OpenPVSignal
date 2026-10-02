# Thesis
Combining ML with KG/ontologies

**Repository Status:** This repository contains some of the source code, including the `requirements.txt` file. Users can 
install dependencies and run `ontology_processing.ipynb`, to create the *base* and *unified* versions of the ontology, manually. 
The remaining source code, with the automated scripts (`setup.bat` and `run.bat` for automated environment setup and 
Jupyter launching), will be fully uploaded within the next two weeks.

## Quick Start

### Prerequisites
- Before running the project, ensure you have the following installed:
    - `JDK` version >= 22.x.x
    - `Python` version: 3.9, 3.10, 3.11, 3.12
    
*Script uses "py": to work `python` launcher is needed*

*`JDK` needs to be in `Environment Variables (PATH)`: To check type `java -version` in cmd and see if it returns the version number without errors*

### Installations 
Run only the first time or to update:
1. Run the file `setup.bat`
2. Wait until the message  ```Setup/Update finished successfully!``` shows in terminal

*Script detects a compatible `Python` version, creates a `virtual environment` and installs all `dependencies` (or updates)*

### Run code
1. Run the file `run.bat`
2. The browser will open automatically the `Jupyter Notebook Interface`
3. Click one of the `.ipynb` files and run the cells to run the code 