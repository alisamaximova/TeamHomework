# Team homework on the subject "Functional Logic and Theory of Algorithms"
## *Bubble and Heap sorts*
### The purpose of the work:

> Investigation of the time complexity of sorting algorithms 
> in conditions of limited hardware resources

### The course of solving the team homework

The team task consisted of several stages: writing code, testing code, recording sorting times, 
plotting graphs and algorithmic schemes, as well as filling out a report and working with a presentation. 
During the homework, each of the team members was involved.

> Alice Maksimova - manager  
> David Bagdasarov - programmer  
> Nguyen Quang Hien - programmer  
> Evgeny Chelnokov - program tester  
> Anastasia Minasova - technical writer  

### *Bubble Sort*

Bubble sorting or sorting by simple exchanges is one of the quadratic array sorting algorithms. 
In terms of implementation and understanding, it is simple, but effective only for small arrays. 
Therefore, its time complexity is O(n^2)

This sorting method is practically not used in practice, but it underlies other more advanced ones, for example, fast and pyramidal.
![hippo](https://codelessons.ru/wp-content/uploads/Animationfotsait.gif)

### *Heap Sort*

Pyramid sorting or heap sorting is a sorting method based on such a data structure as a binary heap – a complete binary tree in which all elements are stored in a special order.

Pyramid sorting is one of the methods whose performance is estimated as O(n log(n)) 
The amount of service memory used does not depend on the size of the array O(1), which is a big plus. 
In all cases, its proven time complexity is O(n log(n))

![hippo](https://tproger.ru/s3/uploads/2017/09/Heap-Sort.gif)

After writing the program code and testing it on a different number of elements of the sorted array, we built graphs of the time complexity of each of the sorting algorithms. 
They show that the discrepancy with the theoretical graphs is insignificant, each of the sorts coincides in time complexity with what we were supposed to get.

![Screenshot](BubbleSort.jpg)
![Screenshot](HeapSort.jpg)