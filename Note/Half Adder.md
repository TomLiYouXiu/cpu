| A | B | S | C |
| - | - | - | - |
| 0 | 0 | 0 | 0 |
| 1 | 0 | 1 | 0 |
| 0 | 1 | 1 | 0 |
| 1 | 1 | 0 | 1 |
AB为输入，S为总和，C为进位
以上为一个半加器的真值表
总结出来关系为 ：
S = A 异或 B
C = A 与 B
半加器的实现如下
![](https://pic.imgdb.cn/item/6405ee47f144a010079b50b9.jpg)
异或门的实现
![](https://pic.imgdb.cn/item/6405ee94f144a010079bc8ab.jpg)