# Exercicio Prismas e Tronco de Piramide
# A parte do Tronco de Piramide

# Python 3.x code to demonstrate star pattern
 
# Function to demonstrate printing pattern
def pypart(n):
     
    # outer loop to handle number of rows
    # n in this case
    for i in range(0, n):
     
        # inner loop to handle number of columns
        # values changing acc. to outer loop
        for j in range(0, i+1):
         
            # printing stars
            print("* ",end="")
      
        # ending line after each row
        print("\r")
 
# Driver Code
n = 5
pypart(n)

# Python 3.x code to demonstrate star pattern
 
# Function to demonstrate printing pattern
def pypart(n):
    myList = []
    for i in range(1,n+1):
        myList.append("*"*i)
    print("\n".join(myList))
 
# Driver Code
n = 5
pypart(n)

# Python 3.x code to demonstrate star pattern
 
# Function to demonstrate printing pattern
def pypart2(n):
     
    # number of spaces
    k = 2*n - 2
 
    # outer loop to handle number of rows
    for i in range(0, n):
     
        # inner loop to handle number spaces
        # values changing acc. to requirement
        for j in range(0, k):
            print(end=" ")
     
        # decrementing k after each loop
        k = k - 2
     
        # inner loop to handle number of columns
        # values changing acc. to outer loop
        for j in range(0, i+1):
         
            # printing stars
            print("* ", end="")
     
        # ending line after each row
        print("\r")
 
# Driver Code
n = 5
pypart2(n)

# Python 3.x code to demonstrate star pattern
 
# Function to demonstrate printing pattern triangle
def triangle(n):
     
    # number of spaces
    k = n - 1
 
    # outer loop to handle number of rows
    for i in range(0, n):
     
        # inner loop to handle number spaces
        # values changing acc. to requirement
        for j in range(0, k):
            print(end=" ")
     
        # decrementing k after each loop
        k = k - 1
     
        # inner loop to handle number of columns
        # values changing acc. to outer loop
        for j in range(0, i+1):
         
            # printing stars
            print("* ", end="")
     
        # ending line after each row
        print("\r")
 
# Driver Code
n = 5
triangle(n)

# Python 3.x code to demonstrate star pattern
 
# Function to demonstrate printing pattern of numbers
def numpat(n):
     
    # initialising starting number 
    num = 1
 
    # outer loop to handle number of rows
    for i in range(0, n):
     
        # re assigning num
        num = 1
     
        # inner loop to handle number of columns
            # values changing acc. to outer loop
        for j in range(0, i+1):
         
                # printing number
            print(num, end=" ")
         
            # incrementing number at each column
            num = num + 1
     
        # ending line after each row
        print("\r")
 
# Driver code
n = 5
numpat(n)

# Python 3.x code to demonstrate star pattern
 
# Function to demonstrate printing pattern of numbers
def contnum(n):
     
    # initializing starting number 
    num = 1
 
    # outer loop to handle number of rows
    for i in range(0, n):
     
        # not re assigning num
        # num = 1
     
        # inner loop to handle number of columns
        # values changing acc. to outer loop
        for j in range(0, i+1):
         
            # printing number
            print(num, end=" ")
         
            # incrementing number at each column
            num = num + 1
     
        # ending line after each row
        print("\r")
 
n = 5
 
# sending 5 as argument
# calling Function
contnum(n)

# Python 3.x code to demonstrate star pattern
 
# Function to demonstrate printing pattern of alphabets
def alphapat(n):
     
    # initializing value corresponding to 'A' 
    # ASCII value
    num = 65
 
    # outer loop to handle number of rows
    # 5 in this case
    for i in range(0, n):
     
        # inner loop to handle number of columns
        # values changing acc. to outer loop
        for j in range(0, i+1):
         
            # explicitely converting to char
            ch = chr(num)
         
            # printing char value 
            print(ch, end=" ")
     
        # incrementing number
        num = num + 1
     
        # ending line after each row
        print("\r")
 
# Driver Code
n = 5
alphapat(n)

# Python code 3.x to demonstrate star pattern
 
# Function to demonstrate printing pattern of alphabets
def  contalpha(n):
     
    # initializing value corresponding to 'A' 
    # ASCII value
    num = 65
 
    # outer loop to handle number of rows
-   for i in range(0, n):
     
        # inner loop to handle number of columns
        # values changing acc. to outer loop
        for j in range(0, i+1):
         
            # explicitely converting to char
            ch = chr(num)
         
            # printing char value 
            print(ch, end=" ")
         
            # incrementing at each column
            num = num +1
     
     
        # ending line after each row
        print("\r")
 
# Driver code
n = 5
contalpha(n)

# Python 3.x code to demonstrate star pattern
 
# Function to demonstrate printing pattern
def pypart(n):
     
    # outer loop to handle number of rows
    # n in this case
    for i in range(0, n):
     
        # inner loop to handle number of columns
        # values changing acc. to outer loop
        for j in range(0, i+1):
         
            # printing stars
            print("* ",end="")
      
        # ending line after each row
        print("\r")
 
# Driver Code
n = 5
pypart(n)

# Python 3.x code to demonstrate star pattern
 
# Function to demonstrate printing pattern
def pypart2(n):
     
    # number of spaces
    k = 2*n - 2
 
    # outer loop to handle number of rows
    for i in range(0, n):
     
        # inner loop to handle number spaces
        # values changing acc. to requirement
        for j in range(0, k):
            print(end=" ")
     
        # decrementing k after each loop
        k = k - 2
     
        # inner loop to handle number of columns
        # values changing acc. to outer loop
        for j in range(0, i+1):
         
            # printing stars
            print("* ", end="")
     
        # ending line after each row
        print("\r")
 
# Driver Code
n = 5
pypart2(n)

# Python 3.x code to demonstrate star pattern
 
# Function to demonstrate printing pattern triangle
def triangle(n):
     
    # number of spaces
    k = n - 1
 
    # outer loop to handle number of rows
    for i in range(0, n):
     
        # inner loop to handle number spaces
        # values changing acc. to requirement
        for j in range(0, k):
            print(end=" ")
     
        # decrementing k after each loop
        k = k - 1
     
        # inner loop to handle number of columns
        # values changing acc. to outer loop
        for j in range(0, i+1):
         
            # printing stars
            print("* ", end="")
     
        # ending line after each row
        print("\r")
 
# Driver Code
n = 5
triangle(n)

# Python 3.x code to demonstrate star pattern
 
# Function to demonstrate printing pattern of numbers
def numpat(n):
     
    # initialising starting number 
    num = 1
 
    # outer loop to handle number of rows
    for i in range(0, n):
     
        # re assigning num
        num = 1
     
        # inner loop to handle number of columns
            # values changing acc. to outer loop
        for j in range(0, i+1):
         
                # printing number
            print(num, end=" ")
         
            # incrementing number at each column
            num = num + 1
     
        # ending line after each row
        print("\r")
 
# Driver code
n = 5
numpat(n)

# Python 3.x code to demonstrate star pattern
 
# Function to demonstrate printing pattern of numbers
def contnum(n):
     
    # initializing starting number 
    num = 1
 
    # outer loop to handle number of rows
    for i in range(0, n):
     
        # not re assigning num
        # num = 1
     
        # inner loop to handle number of columns
        # values changing acc. to outer loop
        for j in range(0, i+1):
         
            # printing number
            print(num, end=" ")
         
            # incrementing number at each column
            num = num + 1
     
        # ending line after each row
        print("\r")
 
n = 5
 
# sending 5 as argument
# calling Function
contnum(n)

# Python 3.x code to demonstrate star pattern
 
# Function to demonstrate printing pattern of alphabets
def alphapat(n):
     
    # initializing value corresponding to 'A' 
    # ASCII value
    num = 65
 
    # outer loop to handle number of rows
    # 5 in this case
    for i in range(0, n):
     
        # inner loop to handle number of columns
        # values changing acc. to outer loop
        for j in range(0, i+1):
         
            # explicitely converting to char
            ch = chr(num)
         
            # printing char value 
            print(ch, end=" ")
     
        # incrementing number
        num = num + 1
     
        # ending line after each row
        print("\r")
 
# Driver Code
n = 5
alphapat(n)

# Python code 3.x to demonstrate star pattern
 
# Function to demonstrate printing pattern of alphabets
def  contalpha(n):
     
    # initializing value corresponding to 'A' 
    # ASCII value
    num = 65
 
    # outer loop to handle number of rows
-   for i in range(0, n):
     
        # inner loop to handle number of columns
        # values changing acc. to outer loop
        for j in range(0, i+1):
         
            # explicitely converting to char
            ch = chr(num)
         
            # printing char value 
            print(ch, end=" ")
         
            # incrementing at each column
            num = num +1
     
     
        # ending line after each row
        print("\r")
 
# Driver code
n = 5
contalpha(n)

# Parte do Prisma

# Implementation of matplotlib function 
import matplotlib.pyplot as plt 
import matplotlib.tri as tri 
import numpy as np 
     
     
ang = 40
rad = 10
radm = 0.35
radii = np.linspace(radm, 0.95, rad) 
     
angles = np.linspace(0, 4 * np.pi, ang) 
angles = np.repeat(angles[..., np.newaxis], rad, axis = 1) 
angles[:, 1::2] += np.pi / ang 
     
x = (radii * np.cos(angles)).flatten() 
y = (radii * np.sin(angles)).flatten() 
z = (np.sin(4 * radii) * np.cos(4 * angles)).flatten() 
     
triang = tri.Triangulation(x, y) 
triang.set_mask(np.hypot(x[triang.triangles].mean(axis = 1), 
                         y[triang.triangles].mean(axis = 1)) 
                        < radm) 
     
tpc = plt.tripcolor(triang, z, shading ='flat') 
plt.colorbar(tpc) 
plt.prism() 
plt.title('matplotlib.pyplot.prism() function Example', 
                                   fontweight ="bold") 
plt.show() 

# Implementation of matplotlib function 
import matplotlib.pyplot as plt 
import numpy as np 
from matplotlib.colors import LogNorm 
        
dx, dy = 0.015, 0.05
x = np.arange(-4.0, 4.0, dx) 
y = np.arange(-4.0, 4.0, dy) 
X, Y = np.meshgrid(x, y) 
     
extent = np.min(x), np.max(x), np.min(y), np.max(y) 
      
    
Z1 = np.add.outer(range(8), range(8)) % 2
plt.imshow(Z1, cmap ="binary_r", interpolation ='nearest', 
                             extent = extent, alpha = 1) 
     
def geeks(x, y): 
    return (1 - x / 2 + x**5 + y**6) * np.exp(-(x**2 + y**2)) 
     
Z2 = geeks(X, Y) 
     
plt.imshow(Z2, alpha = 0.7, interpolation ='bilinear', 
                                    extent = extent) 
plt.prism() 
plt.title('matplotlib.pyplot.prism() function Example',  
                                  fontweight ="bold") 
plt.show() 
