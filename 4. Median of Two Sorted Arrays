class Solution:
    def findMedianSortedArrays(self, nums1: List[int], nums2: List[int]) -> float: 
        m = len(nums1)
        n = len(nums2)
        nums = []
        for i in range(m):
            nums.append(nums1[i])
        for j in range(n):
            nums.append(nums2[j])
        nums.sort()
        total = m+n
        midpoint = total//2
        if total % 2 == 0:
            return (nums[midpoint-1]+nums[midpoint])/2
        elif total % 2 !=0: 
            return nums[midpoint]
