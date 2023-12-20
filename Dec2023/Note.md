# 算法练习第一天-2023.12.13
第一天写的题目是：  
1. [二分查找](https://leetcode.cn/problems/binary-search/)
2. [移除数组](https://leetcode.cn/problems/remove-element/)   
***

发现的问题有两个：
+ 第一个问题：对于C++写的有点少了，一些头文件、输入输出，函数调用等用法不太熟悉
+ 第二个问题：对于移除数组的暴力解法在思维逻辑上（具体是数组内存和控制上）有一些欠缺，原因是写的太少了，还要继续锻炼  
### 明天晚上继续加油！！
***

# 算法练习第二天
第二天写的题目是：  
1. [有序数组的平方](https://leetcode.cn/problems/squares-of-a-sorted-array/description/)  
2. [长度最小的子数组](https://leetcode.cn/problems/minimum-size-subarray-sum/description/)  
3. [螺旋矩阵II](https://leetcode.cn/problems/spiral-matrix-ii/)
***

# 算法练习第三天
第三天写的题目是：  
1. [移除链表元素](https://leetcode.cn/problems/remove-linked-list-elements/description/)
2. [设计链表](https://leetcode.cn/problems/design-linked-list/description/)
3. [反转链表](https://leetcode.cn/problems/reverse-linked-list/description/)

## 2023.12.16 把这两天的问题一起写吧
+ 首先，在指针的应用上，需要继续深究一下，设置虚拟头指针的时候，不需要进行一个头指针的next操作，这样会导致自己的思考变复杂
+ 其次，在自己的写代码上需要提升debug能力，进行冷静的思考，做到事事巨细
+ 然后，在函数和变量的命名规范上需要提高，做到见名生意
+ 最后，在链表的边界上的越界问题，需要继续思考，对指针的越界也是，会导致爆内存（因为目前写的是C++， 还没想好要找什么类型的工作，就先用C++先写着）
### 还是需要继续坚持下去，这周的后面几天有点事情耽搁了，今天补上
***

# 算法练习第四天-2023.12.17
今天写的题目是：  
1. [两两交换链表中的节点](https://leetcode.cn/problems/swap-nodes-in-pairs/description/)
2. [删除链表的倒数第N个节点](https://leetcode.cn/problems/remove-nth-node-from-end-of-list/description/)
3. [链表相交](https://leetcode.cn/problems/3u1WK4/description/)
4. [环形链表II](https://leetcode.cn/problems/linked-list-cycle-ii/)

**今天本来是一周七天的休息的一天，但是因为前两天有点忙，耽搁了一下，就放到今天做了，详细的总结明天再写吧，周末有点累了**
*** 

# 算法练习第五天-2023.12.18
今天写的题目是：  
1. [有效的字母异位词](https://leetcode.cn/problems/valid-anagram/description/)
2. [两个数组的交集](https://leetcode.cn/problems/intersection-of-two-arrays/)
3. [快乐数](https://leetcode.cn/problems/happy-number/description/)
4. [两数之和](https://leetcode.cn/problems/two-sum/)

+ 今天实际上是第一次接触C++中的Hash Table，但是今天的表现其实感觉非常好（虽然在白天的时候没有写这几个题目，写总结的时候已经是12点多，都到第二天了)，总体的问题上是对哈希表的写法和使用经验不太充足。
+ 今天的第一道题我开始熟悉哈希表的逻辑，第二道题熟悉了哈希表的使用和一些常用判断，例如 .begin()、 .end() 、 set.find(key) != set.end()这几个常用的库函数，然后接下来的第三道题就非常轻松就解决了
+ 最后一道题使用了hash map，我也是第一次接触，然后看了一下答案，也有了思路（使用差值进                 行是否存在的判断），但是在代码上还是不怎么会写，因为这里变成了unordered_map。哈哈哈，很无语

**今天太晚了，明天在写前一天你的总结吧，现在总结也是越写越多了，希望会越来越好**
***

# 算法练习第六天-2023.12.20（本来应该是昨天写的，昨天的最后两道题没做完，留到了今天早上）
今天写的题目是：
1. [四数相加II](https://leetcode.cn/problems/4sum-ii/description/)
2. [赎金信](https://leetcode.cn/problems/ransom-note/description/)
3. [三数之和](https://leetcode.cn/problems/3sum/description/)
4. [四数之和](https://leetcode.cn/problems/4sum/description/)

+ 今天是哈希表的最后一天的联系，哈希表这部分确实有点写的不太好，应该有个时间来进行复习一下，需要多练
+ 在很多算法的代码的思想上需要提高，昨天的部分特别是[三数之和](https://leetcode.cn/problems/3sum/description/)和[四数之和](https://leetcode.cn/problems/4sum/description/)这两个题目上，是个经典的题目，需要继续加强一下
+ 也是在后面的两个题目上的问题，在剪枝思想上需要进行深入思考，把我剪枝的条件思考清楚，在本月月底的时候需要对哈希表的知识进行复习
*** 

# 算法练习第七天-2023.12.20
今天写的题目是：
1. [反转字符串](https://leetcode.cn/problems/reverse-string/)
2. [反转字符串II](https://leetcode.cn/problems/reverse-string-ii/description/)
3. [替换数字](https://kamacoder.com/problempage.php?pid=1064)
4. [反转字符串中的单词](https://leetcode.cn/problems/reverse-words-in-a-string/description/)
5. [右旋转字符](https://kamacoder.com/problempage.php?pid=1065)

今天开始的是对字符串的一些操作。  
卡码网的题目，都是想的自己的方法，并没有和讲解中的题目一直，因此做个记录
```替换数字
3. 替换数字
#include <iostream>
using namespace std;

int main(){
    string s;
    cin >> s;
    for (int i = 0; i< s.size(); i++){
        if (s[i] >= '0' && s[i] <= '9') cout << "number";
        else cout << s[i];
    }
    cout << endl;
}
```

```右旋转字符
5. 右旋转字符
#include <iostream>
#include <algorithm>
using namespace std;

int main(){
    string s;
    int k;
    cin >> k;
    cin >> s;

    // 找到最后第k个位置，然后保存，再把k位置之前的元素后移，把k位置的元素补到前面
    for (int i = 0; i<k; i++ ){
        int right = s.size() -k +i;
        char tmp = s[right];
        for (int j = right -1; j>=i; j--){
            s[j+1] = s[j];
        }
        s[i] = tmp;
    }
    
    cout << s << endl;
    
}
```

+ 今天是字符串类型算法的第二天，有五个题目，说实话呢今天的题目第四题(反转字符串中的单词)有点难，分为三步：
  + 第一步：先去掉字符串中多余的空格，保证字符串的头和尾不存在多余的空格，这道题最重要的是这个函数！！

        ```angular2html
            // deleteExtraSpace函数的思想就是碰到空格就跳过，也就是删除；然后在while循环中利用slow指针将非空格字符前移，在for的下一轮循环中再把空格加上
            // 防止在单词与单词之间存在多个空格进行干扰
            void deleteExtraSpace(string& s){
                int slow = 0;
                for (int i = 0; i<s.size(); i++){
                    if (s[i] != ' '){ //遇到非空格进行处理，即删除所有空格
                        if (slow != 0) s[slow++] = ' '; //手动进行空格控制，即给单词之间添加空格。 slow != 0说明不是第一个单词，需要在单词前添加空格。
                        while (i<s.size() && s[i] != ' '){ //补上该单词，遇到空格说明单词结束。
                            s[slow++] = s[i++];
                        }
                    }
                }
                s.resize(slow);
            }
        ```
+ 主要还是在本科阶段的这些题目做的太少了，代码的特性思路（特殊题的特殊解题思路）上还是要多看多练，不能单纯的靠脑子解决（哈哈哈，第三题和第五题都是靠脑子想出来的）。