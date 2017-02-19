# Cubic Spline Interpolator
A jupyter notebook that interpolates a cubic spline from any set of data points given by the user.

# Usage
First, download the jupyter notebook file.
```
git clone https://github.com/jsondoo/Cubic-Spline-Interpolator.git
```
To try the interpolator, go [here](https://try.jupyter.org) and upload the .ipynb file. 
Or if you have jupyter notebook installed:
```
jupyter notebook
```

Open the file and enter your data points in the first cell into the x and y array. Then click Cell -> Run All. Scroll down to see the beautiful plot :)

# Examples
a) Data points: (0,5), (1,9), (2,2), (3,4)

Input:
```python
x=[0,1,2,3]
y=[5,9,2,4]
```
Output:
<br><img src="https://cloud.githubusercontent.com/assets/21695878/23107736/8d44e412-f6b7-11e6-8dc3-b850ca960a4a.png"/>

b) Data points: (-2,10), (3,48), (5,20), (7.5,33), (10,144), (11,9), (12,27)

Input:
```python
x = [-2, 3, 5, 7.5, 10, 11, 12]    
y = [10, 48, 20, 33, 144, 9, 27]
```
Output:
<br><img src="https://cloud.githubusercontent.com/assets/21695878/23107812/e05d2afa-f6b8-11e6-8467-c5adffa9837b.png"/>


Written in Python 3. Last updated February 19th, 2017.
