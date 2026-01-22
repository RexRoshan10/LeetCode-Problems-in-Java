class Solution {
    public int jump(int[] nums) {
        if(nums.length==0)
            return 0;

        int minlimit=0;
        int maxlimit=0;
        int jumps=0;
        while(maxlimit< nums.length-1)
        {
            int max=0;
            for(int i =minlimit; i<=maxlimit;i++ )
            {
                max=Math.max(max, i+nums[i]);
            }
            minlimit=maxlimit+1;
            maxlimit=max;
            jumps++;
        }
        return jumps;
    }
}
