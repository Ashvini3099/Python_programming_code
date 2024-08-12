```python
x=2 
y=4
x+y 
```




    6




```python
df = 'ashvini'
len(df)
```




    7



first = int (input("enter first :" )) 
second = int (input("enter second :") )
addition = first + second
print(addition)


```python
## calculate the average value of two numbers 
```


```python
a = int(input("enter num :" ))
b = int(input("enter num1 : " ))
average = (a+b) // 2
print(average) 
```

    enter num : 20
    enter num1 :  34
    

    27
    


```python
a = int(input("enter height :" ))
b = int(input("enter base  :" )) 
Area_of_triangle = 0.5 *a*b 
print(Area_of_triangle)

```

    enter height : 20
    enter base  : 10
    

    100.0
    


```python
def area_of_triangle (base , Height):
    return 0.5*base*height 
base = 10 
height = 29
print(f"Area of triangle :{area_of_triangle(base , height)}")

```

    Area of triangle :145.0
    


```python
a= int(input("enter first :" )) 
b = int(input("enter second :")) 
print(a>= b)
```

    enter first : 20
    enter second : 17
    

    True
    


```python
##  Indexing and slicing 
```


```python
my_string = "Hello_world" 
my_string[6]
```




    'w'




```python
list2 = [20,30,40,30,45]
list2[0]
```




    20




```python
set1 = {20,30,40,50,60,30}
set1
```




    {20, 30, 40, 50, 60}




```python
tupl1 = (20,10,30,40,50,60)
tupl1[0]
```




    20




```python
dic1 = {"name" :"Ashvini","age": 29 , "colour" : "blue"} 
print(dic1["name"])
```

    Ashvini
    


```python
a = "shindeashvini" 
a[0:12:2]
```




    'sidahi'




```python
ASh = input("Enter String : ")
print(len(ASh))
```

    Enter String :  sudarshan
    

    9
    


```python
light = "green"
if(light=="red"):
    print("stop")
elif(light == "green"):
    print("go")
elif(light == "yellow"):
    print("look")
```

    go
    


```python
num = 25
if(num %2== 0):
    print("even")
else:
    print("odd")

```

    odd
    


```python
for i in range(0,10):
    print(i)
```

    0
    1
    2
    3
    4
    5
    6
    7
    8
    9
    


```python
for i in range(10):
    if i == 5 :
     continue
print(i)
```

    9
    


```python
numbers = [23,12,44,56,60,88,90]
large_even = None 
for number in numbers:
    if i %2 == 0:
        if large_even is None or number > large_even:
            large_even = number 
print("Largest Number of even is :" , str(large_even))

```

    Largest Number of even is : 90
    


```python
list1 = [12,23,34,45,56,6,7]
list1.pop(2)
```




    34




```python
list1
```




    [12, 23, 45, 56, 6, 7]




```python
list1.copy()
```




    [12, 23, 45, 56, 6, 7]




```python
tuple1 = (12,23,34,44,44,56)
tuple1
tuple1.count(44)
```




    2




```python
    set1 = {12, 23, 34, 44, 44, 56}
set1
```




    {12, 23, 34, 44, 56}



Write a program to ask the user enter the three fav movie in the list .


```python
movies = []
movie1 = input("enter the movie name:")
movie2 = input("enter the movie name:")
movie3 = input("enter the movie name:")

movies.append(movie1)
movies.append(movie2)
movies.append(movie3)
print(movies)
```

    enter the movie name: sirf tum
    enter the movie name: Q
    enter the movie name: dum
    

    ['sirf tum', 'Q', 'dum']
    


```python

```
