# this is my-test

---

## 这是H2标题

> 这是引用说明
>> 代码虐我千万遍，我待代码如初恋！

这是图片 ![这是图片](https://www.zybuluo.com/static/img/my_head.jpg "头像")

**粗体字**    *斜体字*    ~~被删除的文字描述~~

- [ ] 这是所有TODO
  - [X] 已完成项
  - [ ] 未完成项1
  - [ ] 未完成项2

### 代码示例 `javascript`

```javascript
onShareAppMessage(e) {
    console.log(e.from)
    console.log(e.target)
    console.log(e.webViewUrl)
    return {
        title: 'mympvue',
        path: '../index/main',
        complete: function (res) {
            console.log(res)
        }
    }
}
```

### 表格

| Item      |    Value | Qty  |
| :-------- | --------:| :--: |
| Computer  | 1600 USD |  5   |
| Phone     |   12 USD |  12  |
| Pipe      |    1 USD | 234  |

### `html`表格

<table>
  <tr>
    <th rowspan="2">值班人员</th>
    <th>星期一</th>
    <th>星期二</th>
    <th>星期三</th>
    <th>图片IMG标签</th>
  </tr>
  <tr>
    <td>李强</td>
    <td>张明</td>
    <td>王平</td>
    <td><img  src="https://github.com/wendux/fly/raw/master/imgs/node.png" alt="node logo"></td>
  </tr>
</table>

---
        GitHub只支持基本的Markdown语法，经测试不支持：(flow、graphLR)流程图、(gantt)甘特图、(sequence)序列图等，也挺简单够用了！

欢迎来到 [my-test](https://github.com/git10135405/my-test)
