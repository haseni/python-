# python-

import os
import cv2 as cv
path="E:\images"
fileNames=os.listdir(path=path)
filePath=os.path.join(path,fileNames[0])
img=cv.imread(filename=filePath,flags=cv.IMREAD_COLOR)
cv.imshow("image",img)
cv.waitKey(0)
cv.destroyAllWindows("image")
