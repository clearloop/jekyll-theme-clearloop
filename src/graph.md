# 图的结构

有很种互竞争的数据结构，如如 document, tree, tabular, relational.... 甚至是正在发展中的更多。
图表可以创建任何其他数据结构，它是 Gun 能够实现的核心。

### 简述
+ 在图形中，对象从不包含其他对象，只是引用
+ Gun 称这些引用为 'Soul'
+ `Soul`被转化为 Hash Symbol 后，所在的对象被称为 `relations`
+ 图可以形成任何数据结构
+ Gun 非常酷

### 结构
Gun 只实现两层结构，如果想要在对象中添加对象，必须先命名对象然后再引用它。

```javascript
var structure = {
    foo: {
        text: "hello" 
    }, 
    bar: {
        text: world
    },
    world: {
        text: "world"
    }
};
```

### 冲突解决
```json
var structure = {
    "ckxAzmBrErR1": {
        text: "hello"
    },
    "qx8QuUBturo8": {
        text: "u12wN9znw50y"
    },
    "u12wN9znw50y": {
        text: "world"
    }
}
```

这些生成的唯一值被称为 `Soul`, `Soul` 驱动着整个系统。
把 `Soul` 包装在对象中的原因是为了与字符串区分。
这些对象被称为 `relate`，包含了 `"#": "a0CLhos5ADx3"` 这样的 hash sign。


