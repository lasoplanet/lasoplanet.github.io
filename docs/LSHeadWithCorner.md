# `<LSHeadWithCorner />`

> 组件路径：`/App/Components/Common/Widgets/LSHeadWithCorner.js`

带有尖角的头像框，可以随意自定义宽高，
目前只支持尖角朝向左或右，如果有需求可以做朝其他方向的

# Props

| 属性            | 类型   | 默认值    | 必填 | 描述                           |
| --------------- | ------ | --------- | ---- | ------------------------------ |
| height          | number | 84        | ❌   | 组件高度                       |
| width           | number | -         | ❌   | 组件宽度，默认是高度的 1.22 倍 |
| arrowLeft       | bool   | false     | ❌   | 箭头方向                       |
| backgroundColor | string | '#1542FF' | ❌   | 背景颜色                       |
| headUrl         | string | -         | ✅   | 头像 url                       |
| headBorderWidth | number | 4         | ❌   | 头像边框宽度                   |
| objectProp      | shape  | -         | ❌   | 对象属性                       |
