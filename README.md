<!--
 * @Author: Aydon
 * @Date: 2020-11-02 15:31:17
 * @LastEditors: Aydon
 * @LastEditTime: 2020-11-02 15:46:29
 * @Description: file content
 * @FilePath: \todo-app\README.md
-->
# Todo-Vue-APP

学习 Vue 制作基于 Vue 的 Todo-APP 基于 [HelloVue-todo-tutorial](https://github.com/HelloGitHub-Team/HelloVue-todo-tutorial) 项目，记录学习日程。

## 第1节 Hello Vue

完成时间: 2020/11/2

练习1:

```javascript
send: function () {
    if (!this.count) {
        alert("请输入内容")
        return
    }
    alert("发送成功")
    this.value = ""
}
```

练习2:

```html
<div v-if="count">
    value 的值是: {{ value }}
</div>
```