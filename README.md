#PROGRAM TO FIND THE AREA OF THE CIRCLE
r=float("Enter the radius of the circle"))
Area=3.14*r*r
print("The Area of the circle with radius",r,"is",Area)

#PROGRAM TO ACCEPT A FILENAME FROM THE USER AND PRINT THE EXTENSION OF IT
Filename=input("Enter the Filename")
F_extension=Filename.split(".")
print("the extension of the file is:"+repr(f_extension[-1]))
