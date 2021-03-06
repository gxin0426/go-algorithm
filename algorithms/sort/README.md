排序：
将多个元素按照一定规则的顺序进行排列。

如：
数值排序
字母排序
优先级排序

分析：
排序则必有先后大小高低，基本操作是：将元素通过比较来调整位置。

排序本质是消除逆序。采用“交换相邻元素”的办法来消除逆序，每次正好只消除一个，因此必须执行O(N^2)的交换次数。
基于交换元素的排序要想突破这个下界，必须执行一些比较，交换相隔比较远的元素，使得一次交换能消除一个以上的逆序。这样才能降低时间复杂度。

[可视化](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)

![时间复杂度](https://github.com/hustcc/JS-Sorting-Algorithm/raw/master/res/sort.png)