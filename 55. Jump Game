class Solution {
    public boolean canJump(int[] nums) {
        int near=0;
        int far=0;
        int farthest=0;

        if(nums.length==1)
            return true;

        while(far<nums.length-1)
        {
            int max=0;
            for(int i = near; i <=far;i++)
            {
                max=Math.max(max,i+nums[i]);
                
            }
            if(max <= far)
                    return false;
            near=far+1;
            far=max;

        }
        return true;
        
    }
}
