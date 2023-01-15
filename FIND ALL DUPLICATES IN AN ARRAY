class Solution {
public:
    vector<int> findDuplicates(vector<int>& nums) {
        vector<int>ans;
        int a=0;
        sort(nums.begin(),nums.end());
        for(int i=0;i<nums.size();i++)
        {
            if(a==nums[i])
            {
                ans.emplace_back(nums[i]);
            }
            a=nums[i];
        }
        return ans;
    }
};
