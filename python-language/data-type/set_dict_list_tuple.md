---
outline: deep
---

# 数据类型（列表、集合、元组、字典）

## 元组 Tuple

### Tuple 定义

> tuple,()

**元组（tuple）**：是**数据结构**，它是一种有序的、可变长度的集合，集合中的元素可以是任意类型。
符号：**（** 、 **）**

::: tip 注意
元素有顺序，可以是任意类型，可重复，**不可修改(顶级元素不可修改，对象嵌套、数组嵌套可修改)** *
:::

## 集合 Set

### Set定义

> set,{}

::: tip 注意
元素无顺序（无序性），不可变（确定性），不可重复（唯一性），常用于去重复
:::

**元素无顺序（无序性）**:集合中的元素无序是指新增元素或者初始定义的元素集合在输出后不确定位置，集合内部会按照固定排序方式进行排列集合元素;
**元素不可变（确定性）**:集合中的元素不能修改和删除，里面的元素为不可变数据类型;

### 常见操作

1. 创建集合：set()
2. 添加元素：add()
3. 删除元素：remove()
4. 集合长度：len()
5. 交集：intersection()
6. 差集：difference()
7. 集合并集：union()

## 字典 dict

### Dict定义

> dict,{},

::: tip 注意
特点：元素为key-value键值对，成对出现；
元素无顺序（无序性），key不可变(确定性)和不可重复（唯一性），value不限制数据类型;
:::
