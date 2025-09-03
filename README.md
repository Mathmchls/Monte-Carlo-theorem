import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import random
import math
import matplotlib.pyplot as plt


rayon = 5
xc = 5
yc = 5
zc=5

n=20


for a in range(n):

  x = random.randint(-10,10)
  y = random.randint(-10,10)
  z = random.randint(-10,10)
  print(x,y,z)

  distance = math.sqrt((x-xc)**2+(y-yc)**2+(z-zc)**2)

  if distance < rayon:
    print("dans le cercle")
  else:
  print("hors du cercle")

