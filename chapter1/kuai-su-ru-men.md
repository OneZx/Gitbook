
### 1. 标题

* 使用`#`号加上一个`空格`

```
# h1
## h2 
### h3
#### h4
##### h5 
###### h6
```

- 效果如下

# h1

## h2

### h3

#### h4

##### h5

###### h6

---

### 2. 列表

> **无序列表**, 使用`-`,`+`,`*`加上一个`空格`

```
- 我是无序列表1
- 我是无序列表2
- 我是 -
+ 我是 +
* me too *
```

效果如下

* 我是无序列表1
* 我是无序列表2
* 我是 -
* 我是+
* me too \*

<br>
> **列表的分层嵌套**

```
- 我是父列表
    - 我是子列表
    - 我是子列表
    - 我是子列表
```

效果如下

* 我是父列表
  * 我是子列表
  * 我是子列表
  * 我是子列表
  
<br>
> **有序列表**, 使用数字`1,2,3...`加上一个`空格`

```
1. 我是有序列表1
2. 我是有序列表2
3. 我是有序列表3
  1. 我是嵌套的列表1
  2. 我是嵌套的列表2
  3. 我是嵌套的列表3
```

效果如下

1. 我是有序列表1
2. 我是有序列表2
3. 我是有序列表3
   1. 我是嵌套的列表1
   2. 我是嵌套的列表2
   3. 我是嵌套的列表3

---

### 3.引用

> **引用** ,在`>`后加一个空格,然后添加引用内容.**使用**`>`**添加内容后记得回车换行**

```
> 我是引用哦
```

- 效果如下

> 我是引用哦

---

### 4.粗体, 斜体 , 删除线

> **粗体** ,使用`**`\(两个星号\)或者`__`\(双下划线\)包裹内容

```
** 这是粗体**
__ 这是粗体__
```

- 效果如下

** 这是粗体**  
** 这是粗体**

<br>
> **斜体**, 使用单个`*`或`_`包裹内容

```
*这是斜体*
_这是斜体_
```

效果如下  
_这是斜体_  
_这是斜体_

<br>
> **删除线**, 使用`~~`包裹内容

```
~~我是删除线~~
```

- 效果如下

~~我是删除线~~

---

### 5. 代码块

> **行内代码**,使用``` ``\(键盘数字1左边的符号\)来包裹内容

    `我是行内代码` `function(){}` `def Users:`

- 效果如下  
`我是行内代码`  `function(){}`  `def Users:`

<br>
> **多行代码块**,使用` ``` `包裹内容,后面跟`py,js`等表示什么语言,也可以不加

```
    ```py
        # 我是多行代码块
        from django.urls import include

        path("captcha/", include('captcha.urls'))
    ``````

效果如下

```py
    # 我是多行代码块
    from django.urls import include

    path("captcha/", include('captcha.urls'))
```

---

### 6. 分割线

> **分割线**, 使用`---`,`___`或`***`表示分割线

    ---
    上面是分割线1 `-减号`
    ___
    上面是分割线2 `_下划线`
    ***
    上面是分割线3 `*星号`

- **效果如下:**

---

上面是分割线1 `-减号`

---

上面是分割线2 `_下划线`

---

上面是分割线3 `*星号`


