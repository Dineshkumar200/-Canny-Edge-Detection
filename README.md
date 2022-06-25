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
![s7](https://user-images.githubusercontent.com/75235789/175783917-7c243256-c528-4703-bb45-aa4e6a4878b8.jpg)
![s8](https://user-images.githubusercontent.com/75235789/175783920-623618ed-593a-4224-91bd-7adba21b57c1.jpg)

