# `<BlurWrappedView />`

> 组件路径：`/App/Components/Common/Widgets/BlurWrappedView.js`

模糊组件，针对 Android 做了特殊处理，抹平部分平台差异

# Props

| 属性       | 类型     | 默认值   | 必填 | 描述         |
| ---------- | -------- | -------- | ---- | ------------ |
| showBlur   | bool     | true     | ❌   | 是否显示模糊 |
| blurAmount | number   | 10       | ❌   | 模糊值       |
| blurType   | 'xlight' | 'xlight' | ❌   | 模糊类型     |

## Methods

### Android node 节点渲染完毕, 显示 blurview

```js
blur();
```

### BlurView

```js
renderBlurView();
```

#### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |

### 内容视图

```js
renderContentView();
```

#### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |
