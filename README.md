# Python2
# 1. Create an empty list called my_list
my_list = []

# 2. Append the following elements to my_list: 10, 20, 30, 40
my_list.extend([10, 20, 30, 40])

# 3. Insert the value 15 at the second position in the list
my_list.insert(1, 15)

# 4. Extend my_list with another list: [50, 60, 70]
my_list.extend([50, 60, 70])

# 5. Remove the last element from my_list
my_list.pop()

# 6. Sort my_list in ascending order
my_list.sort()

# 7. Find and print the index of the value 30 in my_list
index_of_30 = my_list.index(30)
print(f"Index of 30: {index_of_30}")

# Print final list for verification
print("Final my_list:", my_list)
