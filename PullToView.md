## `<PullToView />`

### Props

| 属性  | 类型 | 默认值 | 必填 | 描述 |
| ----- | ---- | ------ | ---- | ---- |
| style | -    | {      |

    flex: 1,
    // Android上，不设置这个背景色，貌似会触发onPanResponderTerminate
    backgroundColor: Colors.geneboxWhite,

} | ❌ | - |
| refreshing | - | false | ❌ | - |
| topPullThreshold | - | 2 | ❌ | - |

### Methods

- 回调拿到外部的滑动距离

```js
innerScrollCallback(value);
```

#### Params

|       | 类型 | 描述 |
| ----- | ---- | ---- |
| value | -    | -    |

- 获取 Header 的 ref

```js
getHeaderRef();
```

### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |

- 禁止触摸

```js
setNoTouch();
```

- 重置到初始化状态

```js
resetContainerPosition(duration);
```

#### Params

|          | 类型 | 描述 |
| -------- | ---- | ---- |
| duration | -    | -    |

- 展示全部视图

```js
slideToFullView();
```

- 下滑刷新的高度

```js
slideToRefreshView(toValue);
```

#### Params

|         | 类型 | 描述 |
| ------- | ---- | ---- |
| toValue | -    | -    |

- 重置状态

```js
resetPullView();
```
