# 1480.-Running-Sum-of-1d-Array-LeetCode-Solution

public class Solution {
    public int[] RunningSum(int[] nums) 
{
    for (int i = 1; i < nums.Length; i++)
    {
        nums[i] += nums[i - 1];
    }
    return nums;
}

}
