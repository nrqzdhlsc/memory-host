### 基础

#### 模板字符串

一种新的字符串连接方式，**允许用户在字符串中插入变量**。

其中，JS的任意返回值都可以添加到模板字符串中的`${}`内部。

#### 箭头函数

- 无需`function`关键字
- 通常不需要`return`: 箭头函数指向的内容会自动返回
- 包含一个以上的参数，函数两边的圆括号不可少

实例：

```js
// 单行
var lordify = (firstname, land) => `${ firstname } of ${ land }`

// 多行
var lordify = (firstname, land) => {
  if (!firstname) {
    // ...
  }
  if (!land) {
    // ....
  }
  return `${ firstname } of ${ land }`
}
```







