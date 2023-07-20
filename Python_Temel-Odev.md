# PYTHON TEMEL ÖDEV
# 1.
```PYTHON
def flatten_list(input_list):
    output_list = []
    for item in input_list:
        if isinstance(item, list):
            output_list.extend(flatten_list(item))
        else:
            output_list.append(item)
    return output_list

input_list = [[1, 'a', ['cat'], 2], [[[3]], 'dog'], 4, 5]
output_list = flatten_list(input_list)
print(output_list)
```

# 2.
```PYTHON
def reverse_nested_list(input_list):
    output_list = []
    for item in reversed(input_list):
        if isinstance(item, list):
            output_list.append(reverse_nested_list(item))
        else:
            output_list.append(item)
    return output_list

input_list = [[1, 2], [3, 4], [5, 6, 7]]
output_list = reverse_nested_list(input_list)
print(output_list)
```
