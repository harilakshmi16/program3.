# program3.
numbers=[10,20,30,40,50]
print("original list:",numbers)
numbers.append(60)
print("after append(60):",numbers)
numbers.insert(1,15)
print("after insert(1,15):",numbers)
numbers.remove(20)
print("after remove(20):",numbers)
numbers.pop(2)
print("after pop(2):",numbers)
numbers.extend([70,80])
print("after extend([70,80]):",numbers)
print("count of 20:",numbers.count(20))
print("Index of 50:", numbers.index(50))
numbers.sort()
print("After sort():", numbers)
numbers.reverse()
print("After reverse():", numbers)
copy_list = numbers.copy()
print("Copied List:", copy_list)
print("Length of list:", len(numbers))
print("Maximum value:", max(numbers))
print("Minimum value:", min(numbers))
print("Sum of list:", sum(numbers))
numbers.clear()
print("After clear():", numbers)

Output:
original list: [10, 20, 30, 40, 50]
after append(60): [10, 20, 30, 40, 50, 60]
after insert(1,15): [10, 15, 20, 30, 40, 50, 60]
after remove(20): [10, 15, 30, 40, 50, 60]
after pop(2): [10, 15, 40, 50, 60]
after extend([70,80]): [10, 15, 40, 50, 60, 70, 80]
count of 20: 0
Index of 50: 3
After sort(): [10, 15, 40, 50, 60, 70, 80]
After reverse(): [80, 70, 60, 50, 40, 15, 10]
Copied List: [80, 70, 60, 50, 40, 15, 10]
Length of list: 7
Maximum value: 80
Minimum value: 10
Sum of list: 325
After clear(): []
