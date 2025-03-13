# List Methods and Supported Operators

Lists in Python are dynamic and support various operations.

## Creating a List

```python
my_list = [1, 2, 3, 4, 5]
```

## Adding Elements

```python
my_list.append(6)  # Adds 6 at the end
my_list.insert(2, 10)  # Inserts 10 at index 2
```

## Removing Elements

```python
my_list.remove(10)  # Removes first occurrence of 10
popped = my_list.pop()  # Removes last element
```

## Operators

```python
concatenated = my_list + [7, 8, 9]  # Concatenation
repeated = my_list * 2  # Repetition
```

```python
print(my_list, popped, concatenated, repeated)
```

## Accessing List Values

Lists allow indexing and slicing.

```python
first_element = my_list[0]
last_element = my_list[-1]
sublist = my_list[1:3]  # Elements from index 1 to 2

print(first_element, last_element, sublist)
```

## Checking if a List is Empty

```python
empty_list = []
if not empty_list:
    print("The list is empty")
```

## Iterating Over a List

```python
for item in my_list:
    print(item)
```

## Checking Whether an Item is in a List

```python
if 2 in my_list:
    print("2 is in the list")
```

## Any and All

```python
boolean_list = [True, True, False]
print(any(boolean_list))  # True if any element is True
print(all(boolean_list))  # True if all elements are True
```

## Reversing List Elements

```python
reversed_list = my_list[::-1]  # Slicing method
my_list.reverse()  # In-place reversal
print(reversed_list, my_list)
```

## Concatenating and Merging Lists

```python
list1 = [1, 2, 3]
list2 = [4, 5, 6]
merged = list1 + list2
print(merged)
```

## Length of a List

```python
length = len(my_list)
print(length)
```

## Removing Duplicate Values

```python
unique_list = list(set([1, 2, 2, 3, 4, 4, 5]))
print(unique_list)
```

## Comparison of Lists

```python
list_a = [1, 2, 3]
list_b = [1, 2, 3]
print(list_a == list_b)  # True if elements and order match
```

## Accessing Values in a Nested List

```python
nested_list = [[1, 2], [3, 4], [5, 6]]
print(nested_list[1][0])  # Accessing first element of second list
```

## Initializing a List to a Fixed Number of Elements

```python
fixed_list = [0] * 5  # Creates [0, 0, 0, 0, 0]
print(fixed_list)
```
