# Applications
  <pre>
  <b><a href="https://github.com/teja963/DSA_All_Models/blob/master/Searching%20Sorting/6.%20Repeat%20and%20missing.cpp">Repeated and missing element in O(N)</a></b>
  Traverse the array. While traversing, use the absolute value of every element as an index
  and make the value at this index as negative to mark it visited. If something is already
  marked negative then this is the repeating element.
  To find missing, traverse the array again and look for a positive value.
  
  <b><a href="https://github.com/teja963/DSA_All_Models/blob/master/Searching%20Sorting/7.%20Majority%20element.cpp">Majority element in O(N)</a></b>
   It means the element is repeated morethan N/2 times so half of the array is occupied
   by that element only. Anykind of arrangement we will that element in atmost 1 
   
  <b><a href="https://github.com/teja963/DSA_All_Models/blob/master/Searching%20Sorting/14.%20count%20num%20of%20subarray%20with%20given%20sum.cpp">Subarray with given sum</a></b>
   The basic idea of using map is 0+sum=sum
   any element added to 0(subarray with zero sum) gives the same sum
   So we are tracking of sum which is repeated, that means it contain zero sum
   
  <b><a href="https://github.com/teja963/DSA_All_Models/blob/master/Searching%20Sorting/15.%20missing%20num%20ap.cpp">Missing number in A.P</a></b>
   Basic:
      common diff=0 and it satisifying that diff(B-A)%C==0 and divisiblity(B-A)/C>=0
      
  <b><a href="https://github.com/teja963/DSA_All_Models/blob/master/Searching%20Sorting/16.%20atleast%20trailing%20zeros.cpp">Atleast N trailing zeros in O(log N)</a></b>
   log n means binary search with l=0 and h= 5*n
   we will check the least possible number with N trailing zeros,
   by count number of zeros of that fact number 
      
  </pre>
# STL
  <pre>
  The lower_bound() method in C++ is used to return an iterator pointing to the first element
  in the range [first, last) which has a value not less than val. This means that the function 
  returns the index of the next smallest number just greater than or equal to that number.
  
  pair<vector<int>::iterator1,vector<int>::iterator2>p;
  p = equal_range(v.begin(), v.end(), x);
  </pre>