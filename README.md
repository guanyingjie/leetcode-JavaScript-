# leetcode-JavaScript-
记录准备春招过程，刷题思路，总结

*初级算法题之数组：

从排序数组中删除重复项
------------------

给定一个排序数组，你需要在原地删除重复出现的元素，使得每个元素只出现一次，返回移除后数组的新长度（https://leetcode-cn.com/explore/interview/card/top-interview-questions-easy/1/array/21/）
```javascript
var removeDuplicates = function(nums) 
{
  for(var i=0;i<nums.length-1;i++)
  {
    if(nums[i]==nums[i+1]
    {
      nums.splice(i,1);
      i--;
    }
  }
}
```
百度了一下splice方法，用户数组中添加删除替换新元素，splice（index，howmany,item1.....itemx)
index：从何处添加
howmany:删除多少元素
item：可选，要添加到数组的元素
