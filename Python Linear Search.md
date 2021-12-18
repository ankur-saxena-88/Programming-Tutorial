# Linear Search in Python

<h3> Inside this tutorial </h3> 

<h4> 1. What is Linear Search in Python </h4> 
<h4> 2. Linear Search Algorithm </h4> 
<h4> 3. Python Linear Search Program </h4>

<h3> 1. What is Linear Search in Python </h3>

1. Linear search is a method to find elements within a list.
2. Also known as a sequential searching algorithm.
3. It is just a simple searching algorithm.
4. The linear search algorithm begins from the first element of the list.
5. It starts checking every element untill the expected element is found.
6. If the element is not found in the list, the algorithm traverses the whole list and return "element not found".

<h3> 2. Linear Search Algorithm </h3>

There is a list of n elements and key value to be searched. Below is the linear search algorithm:

```
LinearSearch (list, key):
    for each item in the list:
        if item == value:
            return its index position
    return -1
```

<h3> 3. Python Linear Search Program </h3>

```    
# Program startt

def linearSearch (list1, n, key):
    # Searching list1 sequentially
    for i in range (0, n):
        if (list1[i] == key):
            return i
    return -1

list1 = [4,2,7,1,8,5,9,6,3]
key = 7

n = len (list1)
result = linearSearch (list1, n, key)

if (result == -1):
    print ("Element not found!\n")
else:
    print ("Element found at index: ", result)

# Program end
```

<h4> Output: </h4>
Element found at index:  2
