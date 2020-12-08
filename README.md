# DSList
New Data Structure created by linux term project

# Comparison of Structure

1. Linked list
<img src = "https://user-images.githubusercontent.com/33143335/101429217-be1c8980-3945-11eb-8ae9-91aa725203a1.png"/>

** Total memory usage = 2 * (4byte + 4byte + sizeof(data)) = 16byte + 2*sizeof(data)

2. DSList (Double Storage List)
<img src = "https://user-images.githubusercontent.com/33143335/101429257-da202b00-3945-11eb-8569-84a4fb1ae67c.png"/>

** Total memory usage = 4byte + 4byte + 1byte + 2*sizeof(data) = 9byte * 2*sizeof(data)


*** Existing Doubly Linked List (picture 1) uses 8bytes for each node
*** We devised new data structure that improves preformance in respect of memory usage.
*** We store twice more data in one node and call this "cluster"

# DSList Data Structure
