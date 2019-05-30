### Pandas选取数据

基本数据结构是`Series`表示数组，`DataFrame`类似二维数组。

其中，每个`Series`都带有一个`index`，用于标记不同的元素，`index`可以是字母，中文，从角色上来看，它类似于SQL的主键。

- iloc: 根据标签所在位置，从0开始计数，**选取列**
- loc: 根据具体标签选择列

这里说的标签就是指列名。

![iloc_loc](assets/iloc_loc.png)