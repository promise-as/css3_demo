## `css3`

### 1. 动态选择器

- 不存在于`html`文件中
- 存在于`css`文件中
- 比如`a`标签的`link,visited,hover,active`

### 2. `UI`元素状态伪类选择器

- `input:enabled`和`input:disabled`

### 3. 动画

```js
.rect{
  width: 100px;
  height: 100px;
  background-color: red;
  position: fixed;
  animation: mymove 3s infinite;
}
@keyframes mymove{
  0%  { top: 0; left: 20%; background-color: red}
  25% { top: 0; left: 80%; background-color: blue}
  50% { top: 80%; left: 80%; background-color: green}
  75% { top: 80%; left: 20%; background-color: black}
  100% { top: 0; left: 20%;  background-color: red}
}
// 注意写动画的分段的时候后面不用写分号
```

