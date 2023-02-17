class Solution {
    public void merge(int[] nums1, int m, int[] nums2, int n) {
        int index=0;
        for(int i=m;i<m+n;i++)
        {
            nums1[i]=nums2[index++];//123256
        }
        Arrays.sort(nums1);//[1,2,2,3,5,6]
    }
}
