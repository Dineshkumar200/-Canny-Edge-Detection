# Canny-edge-detection-workshop


## Program:
``` Python
### Developed By:Dineshkumar V
### Register No:212220230013
import cv2
import numpy as np
import matplotlib.pyplot as plt
# Load the image, Convert to grayscale and remove noise
image1=cv2.imread ('dinesh.jpg') 
gray = cv2.cvtColor(image1,cv2.COLOR_BGR2GRAY)
plt.title('GRAY IMAGE')
plt.imshow(gray,cmap = 'gray')
#canny edge detection
canny_edges = cv2.Canny(gray, 120, 150)
plt.imshow(canny_edges,cmap='gray')
plt.title('canny_edges')
plt.axis("off")
plt.show()
```

## Output:

