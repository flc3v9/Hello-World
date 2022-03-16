# Intro to Python  
Return to [Home Page](README.md)  
Other pages: [HTML](HTMLbeginnings.md) | [Turtle Graphics](TurtleGraphics.md) | [JavaScript](JavaScript.md)  

This is a page about one of my first coding projects for _INFOTEC 1000_. One of the first things I ever coded for this course was a simple program in [Python](https://en.wikipedia.org/wiki/Python_(programming_language)) called **Volume of a Cone**.  

For reference, Python is a progamming language that uses indentation for readability. The logo is seen below:  

![Python Logo](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png)

Back to what I was saying, this code is supposed to calculate the volume of a cone. The project is supposed to teach us:  
* The basics of Python
* How to use Python to solve math problems
* How to use _while loops_ in Python  
* How to get user input  

The code I wrote is shown below:
```
import math

def main():
    # radius input
    while True:
        try:
            radius = float(input("Please type in the radius of a cone: "))
        except ValueError:
            print("Please enter only a numerical value for the radius.")
            continue
        if (radius <= 0):
            print("Please enter a positive value for the radius.")
            continue
        else:
            break

    print("\n")
    # height input
    while True:
        try:
            height = float(input("Please type in the height of a cone: "))
        except ValueError:
            print("Please enter only a numerical value for the height.")
            continue
        if (height <= 0):
            print("Please enter a positive value for the height.")
            continue
        else:
            break

    print("\n")
    # main calculation
    volume = math.pi * (radius**2) * (height/3)
    print("The volume of this cone is: ", end="")
    print(volume)

main()
```

The output of the code would result in this:
![cone image](Cone_image.png)  
This sums up my introduction to Python experience. Thank you for reading!