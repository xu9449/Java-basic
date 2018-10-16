[学习笔记](https://github.com/xu9449/JAVA/wiki) 
1. Document your assumptions   
2. Explain your approach and how you intend to solve the problem  
3. Provide code comments where applicable  
4. Explain the big-O run time complexity of your solution. Justify your answer  
5. Identify any additional data structures you used and justfy why you use them  
6. Only provide your best anser to each part of the question

目录  
--- 
 
Class 01  Sorting & Partitioning    
  
Given a sorted array from 0,1,2,3...to n, and there is only one missing number in it, how to find it?   
[经典例题](https://github.com/xu9449/Interesting-Algorithm-_-Java/wiki/%E7%BB%8F%E5%85%B8%E4%BE%8B%E9%A2%981)  
  
Given an array stored in Stack1, how to sort the numbers by using additional two stacks  
[Using one temp stack](https://www.geeksforgeeks.org/sort-stack-using-temporary-stack/)  
  
Selection Sort   
[Code](https://github.com/xu9449/Interesting-Algorithm-_-Java/blob/master/Laioffer%20Code/selectionSort)  
Merge Sort    
[Code](https://github.com/xu9449/Interesting-Algorithm-_-Java/blob/master/Laioffer%20Code/mergeSort)  
  
[MergeSort的四种变种](https://github.com/xu9449/Interesting-Algorithm-_-Java/wiki/MergeSort-%E7%9A%84%E5%9B%9B%E7%A7%8D%E5%8F%98%E7%A7%8D)  
 

Quick Sort  
[Move 0s To The End I](https://github.com/xu9449/Interesting-Algorithm-_-Java/wiki/Move-0s-to-the-End-I)   
总结：比如 swap (array, L ++, R --)会在运行完function之后进行 ++ -- 运算，保证了代码整洁度，且设置左右向中点扫描方式减少了代码运算复杂度

Rainbow Sort (skip)

### Practice Class 01   
final 修饰的是reference reference不能指向其他东西，只能修改指向的内容。  
[Array vs object](https://github.com/xu9449/Interesting-Algorithm-_-Java/wiki/Array-vs-object)

### Recursion I & Binary Search  

[Fibonachi sequence](https://github.com/xu9449/Interesting-Algorithm-_-Java/wiki/Fibonacci-sequence)  
Example question: [how to calculate a^b](https://github.com/xu9449/Interesting-Algorithm-_-Java/wiki/how-to-calculate-a%5Eb)
int 是 primitive type， 不可能是null。  
考虑括号里是小于还是小于等于的时候，考虑只有一个元素的时候。检查base case  
Binargy Search  
[Variant 1.1 how to find an element in the array that is clsest to the target number? ](https://github.com/xu9449/Interesting-Algorithm-_-Java/wiki/variant-1.1.-how-to-find-an-element-in-the-array-that-is-closest-to-the-target-number%3F)  
[Variant 1.2 return the index of the index of the first occurrence of an element](https://github.com/xu9449/Interesting-Algorithm-_-Java/wiki/Variant-1.2-return-the-index-of-the-first-occurrence-of-an-element)  
Variant 1.4 return how to find closest k elements in the array that is closest to a target number?  
step1: binary search  
step2: 谁小移谁  
Time = O(log (n) + k)  
Solution 2 : optimization O (log n + log k)  
Binarey Search Variant 2.9 :  


