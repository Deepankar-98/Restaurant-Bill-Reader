# Restaurant Bill Reader

### Table of Content
1. [Installation](#installation)
  - [Checking Wand](#checking-Wand)
  - [Checking Pytesseract](#checking-pytesseract)
  



## Installation
In this project `Python` version **3.7.7** is used.

First create a new anaconda environment and then activate the environment:
```python
# Create environmemt.
conda create -n bill-reader python=3.7
# Activate environment.
conda activate bill-reader
```

Then install the following python packages using pip:

`$ pip install wand`

`$ pip install pytesseract`

`$ pip install opencv-python`

---

  #### Checking Wand
  
  **STEP-1**
  
  Open Python terminal by typing the following command in anaconda command prompt:
  `$ python`
  
  This will open a python terminal.

  **STEP-2**

  ```python
  from wand.image import Image as wi
  ```
  
  If you get error any error proceed to **Step-3**:
  
  ![Wand Error Images](/readme-assets/wand-error.jpg)
  
  Visit the following [link](https://docs.wand-py.org/en/latest/guide/install.html) and follow the instructions given for your respective OS.
  
  For [Wndows](https://docs.wand-py.org/en/latest/guide/install.html#install-imagemagick-on-windows).
  
  And then check again repeat Steps 1 and 2. Hopefully it will solve the import error with wand module.
  
  **STEP-3**
  
  If there is no error, then wand module is working fine.
  And we will exit the terminal.

  ```python
  quit()
  ```
  
  ---
  
  ### Checking pytesseract
 
  **STEP-1**
  
  Open Python terminal by typing the following command in anaconda command prompt:
  `$ python`
  
  This will open a python terminal.

  **STEP-2**

  ```python
  import pytesseract
  ```
  
  If you get error any error proceed to **Step-3**:
  
 
 
 
