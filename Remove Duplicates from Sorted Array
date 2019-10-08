/*題目為"排序"後的陣列，因此只需要判斷前(後)項是否重複，而無須擔心有[1,2,2,1]情形
  技巧 : 與前項不同則(往前到重複位置)保留*/
class Solution {
    public int removeDuplicates(int[] nums) {
        if(nums.length==0){//若無長度則不浪費時間
            return 0;
        }
        
        int index = 0;
        for(int i = 1; i < nums.length; i++){
            if(nums[i] != nums[index]){     //與前項不同 
                index++;
                nums[index] = nums[i];      //保留          
            }            
      
/*         else{     //與前項相同                       
                則 i++即可 無需做其他操作    
            }
*/
        }
        //index長度為配合陣列索引值而會差1，需要加回來表示正確長度
        return index+1;
    }
}
