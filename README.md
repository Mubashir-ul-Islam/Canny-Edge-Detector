# Canny-Edge-Detector using python
This repository contain python code to find edges from the given image without using any built-in functions.

Notebook named **`Source_Code.ipynb`** contains the code to find edges by using `Canny Edge Detection` method with step by step.

## Requirements:
`Python 2 or 3`\
`Numpy`\
`matplotlib`\
`imageio`\
`cv2`\
`math`

## How to run code:
Run code from the notebook, it will read `img_1.jpg` by default from `Dataset` folder (If you want to add your custom image then place it in the `Dataset` 
folder and put its name inplace of the old name in notebook).
Run the given Jupyter notebook, it will generate all images and save them in the `Result` folder (You can also see the results in the notebook).

## Steps followed in the given code:
### Step 1:
`Gaussian mask` of desired sigma value is generated.
### Step 2:
Applying `Gaussian mask` to make the input image smooth.
### Step 3:
Compute image derivative `fx` and `fy`
![image text](https://github.com/Mubashir-ul-Islam/Canny-Edge-Detector/blob/main/Readme%20Images/plot_1.jpg)
### Step 4:
![image text](https://github.com/Mubashir-ul-Islam/Canny-Edge-Detector/blob/main/Readme%20Images/plot_2.jpg)
### Step 5:


![image text](https://github.com/Mubashir-ul-Islam/Canny-Edge-Detector/blob/main/Readme%20Images/plot_3.jpg)
### Step 6:


![image text](https://github.com/Mubashir-ul-Islam/Canny-Edge-Detector/blob/main/Readme%20Images/plot_4.jpg)
### Step 7:


![image text](https://github.com/Mubashir-ul-Islam/Canny-Edge-Detector/blob/main/Readme%20Images/plot_5.jpg)


