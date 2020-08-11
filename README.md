# <u>Restaurant Bill Reader</u>

### Table of Content:

1. [Problem Statement](#problem-statement)
2. [Modules Used](#modules-used)
3. [Solution Approach](#Solution-approach)
4. [Installation](#installation)
    - [Checking Wand](#checking-Wand)
    - [Checking Pytesseract](#checking-pytesseract)
    - [Checking OpenCV](#checking-opencv)

4. [Execution Instructions](#Execution-Instructions)
5. [License](#license)
6. [Version](#version)
7. [Author](#author)
  
----

## Problem Statement

In this problem we are given a bunch of resturant bills in pdf format. We have to extract text from the images of bills given in ".pdf" form.

----

## Modules Used

The major python modules used for solving the above mentioned problem are as follows:

- Wand
- OpenCV
- PyTesseract OCR

----

## Solution Approach

1. Use Wand to conver pdd to image of any resolution (here we have used **700 x 700**) and save it in `images` folder.

2. Read the image using OpenCV 

3. Use PyTesseract to read text from the images and save the data obtained as a json file.

----

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

----


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
  
  
  Checkboxes that must be ticked while installing are as follows:
  
  ![Magic Wand Installation](/readme-assets/magic-wand-options.PNG)
  
  And then check again repeat Steps 1 and 2. Hopefully it will solve the import error with wand module.
  
  **STEP-3**
  
  If there is no error, then wand module is working fine.
  And we will exit the terminal.

  ```python
  quit()
  ```
  
  **STEP-4**
  Now open `01-pdf-to-image.ipynb` file and run the cells in your jupyter-notebook.
  
  If you get `DelegateError`, do the follows:
   - INSTALL [GHOSTSCRIPT](https://www.ghostscript.com/download/gsdnld.html)
  
  
  ---
  
  ### Checking pytesseract
 
  **STEP-1**
  
  Open Python terminal by typing the following command in anaconda command prompt:
  `$ python`
  
  This will open a python terminal.

  **Step-2**:
  
  Visit this [link](https://github.com/UB-Mannheim/tesseract/wiki) and download the write installer according to your python architecture (32 or 64).
  Then install it and make a `note of the installation location`.
  
  Then open '02-image-to-text.ipynb' file and in cell 1 update the path mensioned to your installing location.
  ![Replace location here](/readme-assets/tesseract-loc.png)
 
 ---
 
  ### Checking OpenCV
 
  **STEP-1**
  
  Open Python terminal by typing the following command in anaconda command prompt:
  `$ python`
  
  This will open a python terminal.

  **STEP-2**

  ```python
  import cv2
  ```
  
  If you get error any error proceed to **Step-3**:
  
  Refer this answer -- https://stackoverflow.com/questions/19876079/cannot-find-module-cv2-when-using-opencv
  
  It worked for me.
  
----
  
 ## Execution Instructions
 
1. First run `01-pdf-to-image.ipynb`.

   It will take some time to execute completely depending upon your computer hardware.
 
2. Now run `02-image-to-text.ipynb`. 

   It will also take some time to execute.
 
-----
 
 
  
## License

MIT © 2020 [Deepankar](https://github.com/Deepankar-98)

---


 
## Version

1.0.0

--- 
 
 
 
## Author

The author of this project is [Deepankar](https://github.com/Deepankar-98/Restaurant-Bill-Reader).
