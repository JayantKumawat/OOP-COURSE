# OOP-COURSE
n=(int)(input("Enter the value of n "))
def My_function():
    if(n%2!=0):
        print("Wierd")
    elif( (n%2==0) and (1<n<6)):
        print("Not wierd")
    elif((n%2==0) and (5<n<21)):
        print("wierd")        
    elif((n%2==0) and (20<n)):
        print("Not Wierd") 

My_function() 
