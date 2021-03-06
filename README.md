# CS-499 ePortfolio
## Enhancement Two
For the Data Structures and Algorithms portion of the ePortfolio, I chose to focus on the Binary Search Tree project from the CS 260: Data Structures and Algorithms course. This project was created in the June of 2020 during the 20EW6 term. The project aimed to demonstrate the usage and functionality of Binary Search Trees using the C++ programming language. It allowed users to filter and sort through a file of bids.


I had selected this item because it gives me the opportunity to display my familiarity of the C++ programming language as well as my knowledge of the binary search tree data structure. Initially, this project had limited functionality. Through this artifact, I am able to illustrate my understanding of how I can use the binary tree structure to search, insert, sort, and remove data. Through the refinement process, I aim to improve the efficiency of this artifact. There were methods that were incomplete or did not function as expected. Originally, the method which sorted the bids in order by bid ID was incomplete. At the time of the artifact’s creation, it was not a required function. However, through the enhancement process, I wanted to highlight my ability to use the binary tree structure to sort bids in order by their bid ID. Aside from this, I also aimed to demonstrate my knowledge of other sorting methods such as post and pre order to reorganize the bids. In doing so, it illustrated my understanding of how binary search trees work. For instance, the in order sort prints the left side of the tree, the root, and lastly, the right side. This would allow the program to print the data in order from least to greatest, or alphabetically, as shown by the second binary search tree which was incorporated to sort the bids based on their title. In post order, the left tree is displayed and then followed by the right side and lastly the root. Pre order first visited the root, the left side of the tree and then the right. A second binary search tree was incorporated into this artifact to further improve the efficiency of it. This binary tree utilized the bid title as its key. This enabled the program to order the bids based on title rather than the bid ID. It would allow users to find specific bids much easier. 


Reflecting on the code review, I had stated that I wanted to use this artifact to demonstrate the course objective: “Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices.” . Aside from this objective, I was also able to achieve the following course outcome: “Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources.” . To showcase the first course objective, I incorporated a second binary search tree to improve the efficiency of the program. This inclusion allowed users to find bids easier as they are given the option of sorting bids either alphabetically, in order based on bid ID, post ordered, or pre ordered. The second course objective that I had mentioned is obtained through the correction of memory deallocation. In the code review, I had noticed the lack of memory deallocation and potential memory leak. With further research, I was able to properly deallocate the memory and showcase a security mindset that is able to anticipate design flaws and potential vulnerabilities in software. 


I had conducted a lot of research for this artifact. I began with revisiting binary tree data structure and its concepts. This helped to enhance my understanding of the data structure and how it is used to navigate data. Initially, my understanding of these data structures was quite limited. Through this artifact, I was able to obtain a better perspective of the binary tree data structure. I did find it quite challenging creating the second binary tree structure and in finishing some incomplete methods. Once I had a better understanding of how to use a binary search tree to sort through the bids, it was quite fun using different transversals to navigate the bids. It was enjoyable to see how the different transversals changed how the bids were sorted and ordered. 
 Aside from the research conducted on the data structure, I also researched and reviewed information regarding memory allocation and deallocation. This was a topic briefly discussed in the CS 405: Secure Coding class. I mentioned in the code review that I had suspected  memory leak errors which could hinder the function of the program. In some aspect, this issue was a bit challenging due to unfamiliarity with memory leak errors. Further research demonstrated that memory leak errors commonly occur when memory is allocated, and we forget to deallocate that memory. With that understanding, I was able to identify a couple of areas of which the memory was not deallocated and therefore produced memory leak errors. In my original code, there were instances of node pointers like left and right, that were never deallocated. With the additional binary search tree, more node pointers were allocated memory. The lack of deallocation would create memory issues as the memory usage would be continuously increasing. I was able to resolve this issue by using the delete function: 
 
      if (left) {
         delete left;
      }
      
As seen here, the delete function is used to delete the node pointer, left. Quite similarly, this method is used to deallocate the other node pointers. 


### Artifact Link:

[Data Structures and Algorithms Repository](https://github.com/DIParham/Data-Structures)

### ePortfolio Links:
[Code Review](https://www.screencast.com/t/xoiB2GQ8Jtb7)

[Professional Assessment](https://diparham.github.io/ePortfolio/)

[Software Engineering and Design](https://diparham.github.io/Software-Engineering/)

[Databases](https://diparham.github.io/Databases/)
