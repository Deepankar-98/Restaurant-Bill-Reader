# Restaurant Bill Reader

### Table of Content
1. [Installation](#installation)



### Installation
In this project `Python` version **3.7.7** is used.

First create a new anaconda environment and then activate the environment:
```python
# Create environmemt.
conda create -n bill-reader python=3.6
# Activate environment.
conda activate bill-reader
```

Then install the following python packages using pip:

`$ pip install wand`

`$ pip install pytesseract`

  1. **Checking Wand:**
  
  Open Python terminal by typing the following command in anaconda command prompt:
  `$ python`

  This will open a python terminal.

  ```python
  from wand.image import Image as wi
  ```

  If there is no error, then wand module is working fine.
  And we will exit the terminal.

  ```python
  quit()
  ```

  Else If you get error:
  ![Wand Error Images]("readme-assets/wand-error.jpg")
  
