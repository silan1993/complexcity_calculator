## Array methods with his complexcity

1.  Push - O(1) As it insert to the last index
2.  Pop -O(1) As it removed the last index
3.  shift - O(n) As it add to the 1st index the all the other index has to shift
4.  unshift - O(n) As it removes the 1st element of the array so all the other index has to re index
5.  concat = O(n) as it loop through all the elements of the array and insert
6.  slice = O(n) as it return some particular partion of the array
7.  splice = O(n) as it insert into particular index so reindexing happens
8.  sort = O(n\*log n) as it compares every time with the all elements
9.  forEach/map/reduce/filter = O(n) it loops through all the elements of the array
