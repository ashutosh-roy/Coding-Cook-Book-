# Coding-Cook-Book-
Solutions &amp; Notes for coding problems
_____________________________________________________________________________________ 
<h3>Given a non-empty array of integers, every element appears twice except for one. Find that single one.

Note:

Your algorithm should have a linear runtime complexity. Could you implement it without using extra memory?

Example 1:

Input: [2,2,1]
Output: 1
Example 2:

Input: [4,1,2,1,2]
Output: 4
 </h3>
_____________________________________________________________________________________
<pre> 
<code> 
class Solution(object):
    def singleNumber(self, nums):
        """
        :type nums: List[int]
        :rtype: int
        """
        print(nums)
        print(set(nums))
        return 2 * sum(set(nums)) - sum(nums)
</code> 
</pre> 
_____________________________________________________________________________________       

 

Analogy Used: 2 * (a * b * c) - (a + a + b + c + c) 

Functions Used :  

Set returns a distinct set of numbers in python 

Sum returns the sum 
