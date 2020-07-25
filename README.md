# Restaurant Bill Reader

### Table of Content
1. [Installation](#installation)



### Installation
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

  1. **Checking Wand:**
  
  **STEP-1**
  
  Open Python terminal by typing the following command in anaconda command prompt:
  `$ python`
  
  This will open a python terminal.

  **STEP-2**

  ```python
  from wand.image import Image as wi
  ```
  
  **STEP-3**
  If there is no error, then wand module is working fine.
  And we will exit the terminal.

  ```python
  quit()
  ```

  Else If you get error:
  ![Wand Error Images](/readme-assets/wand-error.jpg)
  
  Visit the following [link](https://docs.wand-py.org/en/latest/guide/install.html) and follow the instructions given for your respective OS.
  
  For [Wndows](https://docs.wand-py.org/en/latest/guide/install.html#install-imagemagick-on-windows).
  
  And then check again repeat Steps 1 to 3. Hopefully it will solve all the errors.  
  
  
  
