import numpy as np
from random import randint
class roadMaker:
    def __init__(self,longitude):
        self.longitude=longitude
        self.positions=np.zeros([longitude,2])
        self.xi=None
        self.y1=None
    def createRoad(self,xMax,yMax):
        xVector=np.random.randint(0,high=xMax,size=[self.longitude,1])
        yVector=np.random.randint(0,high=yMax,size=[self.longitude,1])
        self.positions=np.concatenate((xVector,yVector),axis=0)
        


