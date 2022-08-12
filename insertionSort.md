# Insertion Sort 

### Question

![Ekran Görüntüsü (479)](https://user-images.githubusercontent.com/88425475/184354816-f40e12b5-a5d2-47b0-87a6-b506b9645f93.png)


### Solution

### 1)
* [ 22 , 27 , 16 , 2 , 18 , 6 ]  -> n
* [ 2 , 27 , 16 , 22 , 18 , 6 ]  -> n-1
* [ 2 , 6 , 16 , 22 , 18 , 27 ]  -> n-2
* [ 2 , 6 , 16 , 18 , 22 , 27 ]  -> n-3
* [ 2 , 6 , 16 , 18 , 22 , 27 ]  -> 1


### 2)  Big-O Notation

Big O notation is O(n^2). Because in the worst case, it will go to the last element in the given array.

>  n(n+1)/2   O(n^2) 

### 2)  Big-O Notation


### 3-4)  Time Complexity

> Average case: The number we are looking for is in the middle. <br>
> Worst case: The number we're looking for is at the end. <br>
> Best case:The number we're looking for is at the very beginning of the array.

After the array is sorted, it is included in the 18 average case. Because the middle value is 18.

***





