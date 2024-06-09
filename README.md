# Mainflow-Task1
Set,list, dictionary

# Create a list

my_list = [1, 2, 3, 4]

print("Initial list:", my_list)

# Add an element to the list

my_list.append(6)

print("List after adding an element:", my_list)

# Remove an element from the list

my_list.remove(3) |

print("List after removing an element:", my_list)

# Modify an element in the list

my_list[1] = 20

print("List after modifying an element:", my_list)

Initial list: [1, 2, 3, 4]

List after adding an element: [1, 2, 3, 4, 6]

List after removing an element: [1, 2, 4, 6]

List after modifying an element: [1, 20, 4, 6]
# Create a dictionary

my_dict={"name": 'Nivithaa", "age": 21, "city": 'Coimbatore'}

print("\nInitial dictionary:", my_dict)

# Add an element to the dictionary

my_dict["gender"] = 'Female'

print("Dictionary after adding an element:", my_dict)

# Remove an element from the dictionary

del my_dict["city"]

print("Dictionary after removing an element:", my_dict)

#Modify an element in the dictionary

my_dict["age"] = 20

print("Dictionary after modifying an element:", my_dict)

Initial dictionary: {'name': 'Nivithaa', 'age': 21, 'city': 'Coimbatore'}

Dictionary after adding an element: {'name': 'Nivithaa', 'age': 21, 'city': 'Coimbatore', 'gender': 'Female'}

Dictionary after removing an element: {'name': 'Nivithaa', 'age': 21, 'gender': 'Female'}

Dictionary after modifying an element: {'name': 'Nivithaa', 'age': 20, 'gender': 'Female'}

# Create a set

my_set = [1, 2, 3, 4, 5)

print("\nInitial set:", my_set)

# Add an element to the set

my_set.add(6)

print("Set after adding an element:", my_set)

# Remove an element from the set

my_set.remove(3)

print("Set after removing an element:", my_set)

# Check if an element exists in the set

print("Is 2 in the set?", 2 in my_set)

my_set.remove(4)

my_set.add(10)

print("Set after modifying elements:", my_set)

Initial set: {1, 2, 3, 4, 5}

Set after adding an element: {1, 2, 3, 4, 5, 6}

Set after removing an element: {1, 2, 4, 5, 6}

Is 2 in the set? True

Set after modifying elements: {1, 2, 5, 6, 10}
