# SegmentTree-Algorithm
Here is Presentation of Segment Tree Algorithm and implementation using C++ Programming language

## Problem Defination
Let us consider the following problem to understand Segment Trees. 
We have an array ``` arr[0 . . . n-1]. ``` We should be able to
 * Find the sum of elements from index l to r where ``` 0 <= l <= r <= n-1  ```
 * Change value of a specified element of the array to a new value ``` x  ```
    We need to do ``` arr[i] = x ``` where ``` 0 <= i <= n-1. ```
    
    
## Simple Solution ( Naiive Algorithm )
is to run a loop from l to r and calculate sum of elements in given range. To update a value, simply do ``` arr[i] = x ``` 

The first operation takes ``` O(n) ``` time and second operation takes ``` O(1) ``` time. 


## Representation of SegmentTree
![](representation.png)

## Segment Tree Main Function

* Main function :
  * void BuiltTree(int l , int r , int p = 1) ;
  * void UpdateTree(int l , int r , int i , int j , int val , int p = 1) ;
  * int RangeSumQuery(int l , int r , int i , int j , int p = 1) ;
  * Lazy Propagation Functions : ``` O ( n ) ```
  
## Resourses
 * [Segment Tree | Set 1 (Sum of given range)](http://www.geeksforgeeks.org/segment-tree-set-1-sum-of-given-range/)
 * [Segment Tree | Set 2 (Range Minimum Query)](http://www.geeksforgeeks.org/segment-tree-set-1-range-minimum-query/)
 * [Segment tree](https://en.wikipedia.org/wiki/Segment_tree)
 * [CodeForces Post](http://codeforces.com/blog/entry/15890)
 
