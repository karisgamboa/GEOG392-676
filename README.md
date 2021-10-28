# GEOG392-676
GIS Programming
|Labs    |
|:-------|
|[Lab1](Lab1/README.MD)|
HELLO
|[Lab2](Lab2/README.MD)|
|[Lab3](Lab3/README.MD)|
|[Lab4](Lab4/README.MD)|
|[Lab5](Lab5/README.MD)|
|[Lab6](Lab6/README.MD)|
|[Lab7](Lab7/README.MD)|

# --part 1: Take the following list and multiply all list items together.
# part1 = [1, 2, 4, 8, 16, 32, 64, 128, 256, 512, 1024, 2048, 4096]

# transversal method

items1 = [1, 2, 4, 8, 16, 32, 64, 128, 256, 512, 1024, 2048, 4096] # 13 elements that will all be multiplied together
result = 1 # variable that starts with 1
for k in items1: # loop statement that extracts each item and stores that value from items1 into variable k
    result=result * k # k represents an element that will keep storing the previous result and then multiply the next item in list 
    print("Product of all numbers:") # prints out the phrase "Product of all numbers:" with each new result
    print(result) # prints each result; final output: 302231454903657293676544
    


# --part 2: Take the following list and add all list items together.
# part2 = [-1, 23, 483, 8573, -13847, -381569, 1652337, 718522177]

# transversal method

items2 = [-1, 23, 483, 8573, -13847, -381569, 1652337, 718522177] # 8 elements that will be added together
sum = 0 # variable that starts with 0
for e in items2: # loop statement that extracts each item and store the value from items2 into variable e 
    sum=sum + e # e represents an element that will keep storing the previous result and then add the next item in list
    print("Sum of all numbers:") # prints out the phrase "Sum of all numbers:" with each new result
    print(sum) # prints out sum; final output: 719788176

# --part 3: Take the following list and only add together those list items which are even. 
# part3 = [146, 875, 911, 83, 81, 439, 44, 5, 46, 76, 61, 68, 1, 14, 38, 26, 21] 

items3 = [146, 875, 911, 83, 81, 439, 44, 5, 46, 76, 61, 68, 1, 14, 38, 26, 21] # list of 17 numbers
even = 0 # initializes variable
for number in items3: # loops each element in items3 list
    if not number%2: # modulo operator; checks for a remainder in items3 list by dividing by 2 
        even+= number # addition assignment operator; adds the even values together
        print("Sum of all even numbers:") # prints out the phrase "Sum of all even numbers:"
        print (even) # prints out even sum of even numbers; final output: 458
