I explored a variety of data structures in this research, such as vector sorting, linked lists, hash tables, and binary search trees (BSTs).  Analyzing each data structure's performance in terms of memory utilization, practical applicability, and efficiency (runtime complexity) was the aim.  I gained a better understanding of the significance of selecting the appropriate data structure for various issue types thanks to these implementations.

This project's main challenge was figuring out how to effectively store, retrieve, search, and change data.  For example, it was difficult to easily organize and obtain course information in the course planner.  Different data structures, such as hash tables and BSTs, offered different trade-offs in terms of memory utilization, insertion efficiency, and search time.

I tackled the problem by putting many data structures into practice and evaluating them to see how well they worked in real-world situations.  Because they affect a program's scalability and performance, data structures are essential.

BSTs make it possible to search and sort items efficiently, but if they are not balanced, performance may suffer.
Although hash tables offer quick lookups (O(1) on average), they necessitate effective collision management.
Although linked lists have the advantage of dynamic memory allocation, they also have extra pointer overhead.
Vector sorting is easy, but if you need to enter or remove data often, it might be slow.
I was able to create better solutions depending on the particular requirements of the application by comprehending these trade-offs.


Throughout the project, I encountered several roadblocks:

Managing File I/O for Data Loading:  It took precise string manipulation and error handling to properly parse CSV files.  Processing each line more quickly was made possible by the use of string streams.
Problems with BST Imbalance:  My BST implementation initially produced an imbalanced tree since it performed poorly with sorted data.  Investigating self-balancing trees (such as Red-Black Trees or AVL) yielded information on how to make the method better.
Debugging Hash Collisions: I used chaining (linked lists at each bucket) to overcome collision management issues with the hash table implementation.

I gained a better grasp of data structure optimization by methodically troubleshooting and studying best practices.

Working on this project significantly shaped my software design skills:

Recognizing Trade-Offs: Selecting the appropriate data format is essential.  This project served as more evidence that there is no one-size-fits-all solution; rather, the selection is based on performance requirements, memory limitations, and access patterns.
Writing Maintainable Code: My code was simpler to understand and edit because to the use of modular functions, explicit naming standards, and documentation.
Optimizing Performance: I was able to consider scalability and efficiency while creating software by examining big-O notation for various data structures.

This project helped me write more structured, readable, and adaptable code by:

Using Object-Oriented Design: Encapsulating logic within classes (BinarySearchTree, HashTable) improved reusability.
Improving Error Handling: Proper input validation, exception handling, and clear user prompts made the program more robust.
Commenting and Documentation: Writing meaningful comments and maintaining a structured README ensures that future modifications will be easier.

This project has been a great opportunity to practice using data structures to tackle practical issues.  I'm going to keep honing my strategy for creating software that is scalable, maintainable, and effective. 

