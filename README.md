# Algorithms 📊

List of Algorithms and Examples

## 🐍[Week 1][W1]: Python Fundamentals

The assignment is designed to serve as a practical exercise in deepening your understanding and skills in the Python programming language. Emphasis is placed on grasping core Object-Oriented Programming (OOP) concepts including the creation and utilization of classes, defining methods, and leveraging the rich syntax that Python offers. Through this assignment, you will not only reinforce your knowledge of fundamental programming constructs but also apply these constructs in the creation of efficient algorithms. Specifically, you will be tasked with developing two distinct search algorithms: a 'simple search', which is a straightforward approach to sequentially look through data, and a more complex 'binary search', which is an advanced technique that divides the data to expedite the search process. Both methods will be used to perform a common, real-world task: retrieving a person's phone number from a dataset when provided with their name.
By implementing both algorithms, you will gain insights into the trade-offs between simplicity and efficiency in programming. The 'simple search' algorithm, while easier to implement, may be less efficient for large datasets. Conversely, the 'binary search' algorithm requires a more intricate understanding of data structures but can significantly speed up the search operation on sorted data. This assignment is an excellent opportunity to apply theoretical OOP principles to a tangible problem, sharpening your ability to write Python code that is not only functional but also well-structured and efficient.

## 📒[Week 2][W2]: Linked List & Selection Sort

This assignment aims to deepen your understanding of two key data structures: Linked Lists and the implementation of the Selection Sort algorithm. You will construct a shopping list application as a practical exercise to compare and contrast the use of simple arrays and linked lists for managing data.The program will be modularized into separate files: simple_array_shopping_list_manager.py will demonstrate how arrays manage shopping items, while linked_list_shopping_list_manager.py will explore the dynamic nature of linked lists. Each file will contain a FileNameClass, like SimpleArrayShoppingList or LinkedListShoppingList, encompassing methods for item manipulation such as adding, removing, and sorting.In the linked list implementation, you'll manually apply the selection sort algorithm, enhancing your grasp of sorting techniques and their application within different structures. This hands-on approach will not only solidify your coding skills but also sharpen your ability to choose appropriate data structures and algorithms for efficient data management.

## 🗼[Week 3][W3]: Stack & Recursive Functions

This assignment is to gain knowledge on **Stack** and **Recursive** functions. A shopping list using Stack will be implemented for this exercise. The program stores shopping items in both simple array or linked list-based Stack.

Each storing mechanism is separated into different files, such as `simple_array_shopping_list_manager.py` or `linked_list_shopping_list_manager.py`, where each file contains `FileNameClass` classes with essential methods for data manipulation.

## :octocat:[Week 4][W4]: Quicksort

This assignment is to gain knowledge on quicksort using a linked list. A shopping list will be reimplemented for this exercise. The program stores shopping items in both simple arrays and linked lists utilizing different methods for either. Each storing mechanism is separated into different files, such as `simple_array_shopping_list_manager.py` or `linked_list_shopping_list_manager.py`, where each file contains FileNameClass classes with essential methods for data manipulation.

## 🧮[Week 5][W5]: Hash Tables using Simple Array

This assignment is to gain knowledge on hash tables using a simple array along with a linked list. A grocery store inventory manager will be implemented for this exercise. The program stores inventory items in hash tables. Each storing mechanism is separated into different files, such as [simple_array_grocery_store_inventory.py][simp] or [`hash_grocery_store_inventory.py`][hash], where each file contains FileNameClass classes with essential methods for data manipulation. 

## 🍞 [Week 6][W6]: Breadth-First Search

This assignment is to gain knowledge on the Breadth-first search using a queue. Given a 2D grid map of '1's (land) and '0's (water), count the number of islands. An island is surrounded by water and is formed by connecting adjacent lands horizontally or vertically. You may assume all four edges of the grid are all surrounded by water. 

## 🤓💻 [Week 7][W7]: Dijkstras Algorithm

This assignment is to learn about the Dijkstra algorithm. Given a hash graph map from the dijkstra_main.py, complete the functions in the separate "DijkstraClass" class within dijkstra.py. The main object of the "DijkstraClass" is to find the lowest-cost path from the start (s) to finish (f). 

## 🏴‍☠️ [Week 8][W8]: Treasure Hunter Class

Given a hunters and treasures locations from the `treasure_hunter_main.py`, complete the functions in the separate `TreasureHunterClass` class within `treasure_hunter.py`.
The main object of the `TreasureHunterClass` is to find the maximum treasures with given hunters.

A `treasure` + `hunter` map `array` of size `n` is constructed with the following specifications:

1. Each element in the array contains either a `hunter(H)` or a `treasure(T)`.
2. Each hunter can find only one treasure.
3. A hunter cannot catch a treasure that is more than `K` units away from the hunter.

## 🧮 [Week 9][W9]: Dynamic Programming

Given two string sequences from the longest_common_subseq_main.py, complete the functions in the separate LCSClass class within `longest_common_subseq.py`. The main object of the LCSClass is to find the length of the longest common subsequence.

## 🧔[Week 10][W10]: k-nn

The objective of this assignment is to learn about k-nearest neighbors. Given two data sets, complete the functions in the separate knnWrapperClass class within `knn_wrapper.py`, and edit the parameter on the train method call from the main method to achieve 100% accuracy. The knnWrapperClass object is to implement a k-nearest classifier wrapper and classify test data. In addition, you should use the pandas and KNeighborsClassifier library from sklearn, and you need to achieve a 100% classification rate on test data.

As part of the assignment, provide which 'neighbor' parameter works best for each dataset and describe tips on choosing the 'neighbor' value. Keep in mind to always comment and document your class and methods.

[W1]: /docs/PE01-README.md "Python Fundamentals"
[W2]: /docs/PE02-README.md "Requirements for simple array and linked list"
[W3]: /docs/PE03-README.md "Stack & Recursive Functions"
[W4]: /docs/PE04-README.md "Quicksort"
[W5]: /docs/PE05-README.md "Hash Tables using Simple Array"
[W6]: /docs/PE06-README.md "Breadth-First Search"
[W7]: /docs/PE07-README.md "Dijkstras Algorithm"
[W8]: /docs/PE08-README.md "Treasure Hunt Program"
[W9]: /docs/PE09-README.md "Dynamic Programming"
[W10]: /docs/PE10-README.md "K-NN classifier"
[simp]: /assets/modules/PE05/src/simp_arr_gsi.py "Links to the simple array shooping list manager"
[hash]: /assets/modules/PE05/src/hash_gsi.py "Links to the implementation of the hash function implemented in grocery store inventory"
[gsi]: /assets/modules/PE05/grocery_store_inventory.py
