```py
class Solution(object):
    def findNumbers(self, nums):
        count = 0
        for i in nums:
            s = str(i)
            if len(s) % 2 == 0:
                count += 1
        return count
```

**Approach**

1 - variable named count to store the number of elements with even number of digits

2 - iterating through the list `nums` each element

3 - if len(i)  - length of element is divisible by 2 - `len(i) % 2 == 0` 

if true incremenet count else move to next element

4 - return count 

time complexity - O(n) - iterate through list of length n

space - O(1) - Variable - count
