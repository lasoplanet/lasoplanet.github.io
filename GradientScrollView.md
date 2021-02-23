## `<GradientScrollView />`

### Props

| 属性                  | 类型   | 默认值   | 必填 | 描述 |
| --------------------- | ------ | -------- | ---- | ---- |
| round                 | bool   | false    | ❌   | -    |
| yRange                | number | 120      | ❌   | -    |
| onLeftPress           | func   | null     | ❌   | -    |
| coefficient           | number | 0        | ❌   | -    |
| navBarHeight          | number | null     | ❌   | -    |
| navBarTitle           | string | ''       | ❌   | -    |
| getYOffset            | func   | null     | ❌   | -    |
| style                 | object | {}       | ❌   | -    |
| children              | shape  | -        | ✅   | -    |
| windowHeight          | number | 0        | ❌   | -    |
| resetStatusBar        | object | true     | ❌   | -    |
| onBackgroundLoadEnd   | func   | () => {} | ❌   | -    |
| onBackgroundLoadError | func   | () => {} | ❌   | -    |
| backgroundSource      | object | -        | ✅   | -    |

### Methods

- 顶部大图展示

```js
renderBackground();
```

### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |

- 滑动区域头部视图（暂时未使用）

```js
renderHeaderView();
```

### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |
