# DIPT--workshop-1 : Working on Images
### Instructions for submission 
##### 1. The image should be a plant, Tree, flower or building

##### 2. The filename should be username.jpg

#####  3. The image should be Converted to gray scale and HSV 

##### 4. Display the H, S and V planes
 ## Program
 ```
Developed by: SANDHIYA R
Register Number: 212222230129
```
```python
import cv2
image=cv2.imread('flower.jpg',1)
image=cv2.resize(image,(400,250))
cv2.imshow('Sandhiya R',image)
cv2.waitKey(0)

# The image should be Converted to gray scale
import cv2
image = cv2.imread('flower.jpg')
gray = cv2. cvtColor(image, cv2.COLOR_BGR2GRAY)
cv2. imshow('Sandhiya R', gray)
cv2. waitKey(0)
cv2. destroyAllWindows()

#  The image should be Converted to HSV
import cv2
image = cv2.imread('flower.jpg')
gray = cv2. cvtColor(image, cv2.COLOR_BGR2HSV)
cv2. imshow('Sandhiya R', gray)
cv2. waitKey(0)
cv2. destroyAllWindows()

# Display the H, S and V planes
import cv2
image=cv2.imread("flower.jpg",1)
image= cv2.resize(image,(400,250))
image=cv2.cvtColor(image,cv2.COLOR_RGB2HSV)
H,S,V=cv2.split(image)
cv2.imshow('Hue',H)
cv2.imshow('Saturation',S)
cv2.imshow('Value',V)


```




## Output
### Image
![image](https://github.com/SandhiyaR1/DIPT--workshop-1/assets/113497571/c51f42bf-5592-48a3-8e7e-f765b139ef87)
### The image should be Converted to gray scale
![image](https://github.com/SandhiyaR1/DIPT--workshop-1/assets/113497571/eaabe997-2278-4dfa-971c-077cd2cd3cdf)
### The image should be Converted to HSV
![image](https://github.com/SandhiyaR1/DIPT--workshop-1/assets/113497571/0fcbebea-e350-4bf2-8f22-9e0ab18738f1)
### Display the H, S and V planes
![image](https://github.com/SandhiyaR1/DIPT--workshop-1/assets/113497571/c0b11a77-fb6a-45c2-ace3-3a8d26f81b7f)

![image](https://github.com/SandhiyaR1/DIPT--workshop-1/assets/113497571/ea845656-c532-4783-affe-a9d0f81b4069)

 ![image](https://github.com/SandhiyaR1/DIPT--workshop-1/assets/113497571/42b42714-1910-42c6-874c-1a6ba3aca8cf)
 ## Result
 Thus Working on Images has been performed successfully!!.
