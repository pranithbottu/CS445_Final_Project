# CS445_Final_Project

Introduction
-------------

Requirements
------------
- <a href="https://www.python.org/downloads/">Python</a>
- <a href="https://www.python.org/downloads/">Jupyter Notebook
</a>

Installation
------------
```python
from sklearn.cluster import KMeans
from sklearn.utils import shuffle
import cv2
import ntpath
import os
```

Execution
------------
1. Clone this repository to your local machine
2. Open final_project.ipynb
3. Run the block Import the Required Libraries
4. Run the block Create the ColorBlock Class
5. Change the source image and the parameters 
    
    a. Please notice that the path of the source image has to be in the form of "inputs/sourceimg.jpg".

    b. The higher the parameters are, the more the image will be blur.


```python
portrait = ColorBlock("inputs/person5.jpg", 15, 53, 80)
```
6. Run the block Run the Project
