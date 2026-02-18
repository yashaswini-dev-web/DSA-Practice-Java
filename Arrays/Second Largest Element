class Solution {
    public int secondLargestElement(int[] nums) {
     int firstLargeElement =nums[0];
     int secondLargestElement=nums[1];
       if(nums[0]>nums[1]){
          firstLargeElement=nums[0];
          secondLargestElement=nums[1];
       }
       else if(nums[0]<nums[1]){
        firstLargeElement=nums[1];
        secondLargestElement=nums[0];
       }
       else{
          firstLargeElement=nums[0];
          secondLargestElement=-1;
       }
       for(int i=2;i<nums.length;i++){
          if(nums[i]>firstLargeElement){
            secondLargestElement=firstLargeElement;
            firstLargeElement=nums[i];   
          }
          else if(nums[i]>secondLargestElement && nums[i]!=firstLargeElement){
            secondLargestElement=nums[i];
          }
       }
       return secondLargestElement;
    }
}
