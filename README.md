# 一级标题
## 二级标题
### 三级标题

#### 4.1 字体
**加粗**
*斜体*
***加粗斜体***
~~删除线~~
<u>下划线</u>
<kbd>Ctrl</kbd>

#### 4.2 引用
>引用一
>>引用二
>>>引用三

#### 4.3 分割线
---
***

#### 4.4 图片
![百度LOGO](https://www.baidu.com/img/bd_logo1.png "百度图片")


#### 4.5 超链接
[百度首页](https://www.baidu.com "欢迎访问百度首页！")


#### 4.6 列表
##### 4.6.1 无序列表
- item-1
    1. item-1
    2. item-1
    3. item-1
+ item-2
* item-3
##### 4.6.2 有序列表
1. item-1
    - item-1
    - item-2
    - item-3
2. item-2
    1. item-1
    2. item-2
    3. item-3
3. item-3

#### 4.7 表格
序号|姓名|邮箱地址|备注
:-:|:-:|-:|-
1|张三三|zhangsansan@163.com|Java程序员
2|李四|lisi@163.com|科学家
3|王五|wangwu@163.com|测试工程师
4|赵六|zhaoliu@163.com|DBA

#### 4.8 代码
`s_print("hello world");`

```javascrpt
$(document).ready(function(){
    alert('hello world');
});
```

```sql
select * from t_user u where u.username='zhangsan';
```

#### 4.9 TODO
- [ ] **V1.0**
    - [x] func-1
    - [x] func-2
    - [ ] func-3
- [ ] **V2.0**
    - [ ] func-1
    - [ ] func-2


#### 4.10 流程图
```flow
st=>start: Start
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
```
