<<<<<<< HEAD
# #Starting Array
# tools = ['Laptop', 'Monitor', 'Keyboard', 'Mouse']
=======
<!-- # Lab 385
# #Starting Array
# tools = ['Laptop', 'Monitor', 'Keyboard', 'Mouse']

# # Goal print laptop out of our list
# print(tools[0])

# # Grab mouse from tool kit
# print(tools[-1])

# # Remove monitor and keyboard from my bad but save in a new list
# # Stop index is NOT inclusive
# removed = tools[1:3]
# print(removed)

# # replace monitor with webcam
# tools[1]= 'webcam'
# print(tools)

# # Add a desk to our tools
# tools.append('Desk')
# print(tools)

# #lets add headphones to our tools
# tools.insert(1,'Headphones')
# print(tools)

# # Remove keyboard from our tools
# tools.remove('Keyboard')
# print(tools)

# # how many items are in my tools and save to variable
# number_of_tools = len(tools)
# print(number_of_tools)

# Pass By Reference
og_list = [1, 2, 3]

# THIS IS NOT CREATING A COPY (SHALLOW COPY)
new_reference = og_list

# changes one shallow copy will change the other
new_reference.append(4)

print('Ref list:', new_reference)
print('Og list:', og_list)
print(og_list == new_reference)

# Deep Copys - for when you want to manipulate data without changing source
new_deep_copy = og_list.copy()

new_deep_copy.append(13)
print('Og list:', og_list)
print('Deep Copy:', new_deep_copy)



# Part 3 -------------------------------------
# Lists and Functions
recent_first =  [1989, 1991, 1997, 2000]
recent_last = [2022, 2018, 2016, 2011]

def reorder_years(recentFirst, recentLast):
    recentLast.reverse()

    recentFirst.extend(recent_last)

    return recentFirst

reorder_years(recent_first, recent_last)


>>>>>>> cff85685451d8436ebe78ded3467a8a10eea5b31

# # Goal print laptop out of our list
# print(tools[0])

# # Grab mouse from tool kit
# print(tools[-1])

# # Remove monitor and keyboard from my bad but save in a new list
# # Stop index is NOT inclusive
# removed = tools[1:3]
# print(removed)

# # replace monitor with webcam
# tools[1]= 'webcam'
# print(tools)

# # Add a desk to our tools
# tools.append('Desk')
# print(tools)

# #lets add headphones to our tools
# tools.insert(1,'Headphones')
# print(tools)

# # Remove keyboard from our tools
# tools.remove('Keyboard')
# print(tools)

# # how many items are in my tools and save to variable
# number_of_tools = len(tools)
# print(number_of_tools)

# Pass By Reference
og_list = [1, 2, 3]

# THIS IS NOT CREATING A COPY (SHALLOW COPY)
new_reference = og_list

# changes one shallow copy will change the other
new_reference.append(4)

print('Ref list:', new_reference)
print('Og list:', og_list)
print(og_list == new_reference)

# Deep Copys - for when you want to manipulate data without changing source
new_deep_copy = og_list.copy()

new_deep_copy.append(13)
print('Og list:', og_list)
print('Deep Copy:', new_deep_copy)



# Part 3 -------------------------------------
# Lists and Functions
recent_first =  [1989, 1991, 1997, 2000]
recent_last = [2022, 2018, 2016, 2011]

def reorder_years(recentFirst, recentLast):
    recentLast.reverse()

    recentFirst.extend(recent_last)

    return recentFirst

reorder_years(recent_first, recent_last)

print(recent_first)