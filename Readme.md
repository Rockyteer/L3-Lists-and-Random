## list

A data structure that is mutable (changeable) ordered sequence of elements. Defined by having values between square brackets []

ex:
```python
groceryList=["pie","takis", "dino nuggets","chicken tenders", "cheese", "pineapple", "sausage"]  #list of strings
```

### indexing list
Each item in a list corresponds to an index number, which is an integer, starting from 0

`groceryList[3]` outputs: ---> chicken tenders

`len()` gives us the length/number of items in our list.
`len(groceryList)---->7

### List Functions
List.append(element)----> adds an item to the end of a list

`groceryList.append("bacon")

```python
item = input("Enter a grocery list item: ")
groceryList.append(item) #adds user's input to the end to the list
```
- List.insert(index, element)----> add an item to the specific index location
- `groceryList.insert(0, "water")`
- List.remove(Element)---> searches the list for a specific element and removes it
- `groceryList.remove("pie")`
- `List.pop(Index)--->removes an item at specified index
- `groceryList.pop(3)`

## Random

A clas that random numbers. There is a functiuon that lest the computer pick a random number betwen a given range.

## Formula
```python
import random #import the random package library
``` 
vairable = random.randint(startNum, endNum)

ex:
x=random.randint(0,10)
