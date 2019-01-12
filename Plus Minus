#!/bin/python3

import math
import os
import random
import re
import sys

# Complete the plusMinus function below.
def plusMinus(arr):
    positive=0
    negative=0
    z=0
    li = [elem for elem in arr]
    for elem in li:
        if(elem>0):
         positive+=1
        elif(elem<0):
         negative+=1
        elif(elem==0):
         z+=1
    print(positive/len(li))
    print(negative/len(li))
    print(z/len(li))
     

if __name__ == '__main__':
    n = int(input())
   

    arr = list(map(int, input().rstrip().split()))

    plusMinus(arr)
