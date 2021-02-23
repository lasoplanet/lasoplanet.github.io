# `<ScrollTabBarView />`

> 组件路径：`/App/Components/Common/Widgets/ScrollTabBarView.js`

## Methods

### 初始化状态数据

```js
initData(props);
```

#### Params

|       | 类型  | 描述 |
| ----- | ----- | ---- |
| props | mixed | -    |

### 匹配 Tab 单击事件

```js
onMatchTabPress();
```

### 探索 Tab 单击事件

```js
onExploreTabPress();
```

### 滑动监听

```js
onScrollListener(e);
```

#### Params

|     | 类型 | 描述 |
| --- | ---- | ---- |
| e   | -    | -    |

### 滑动开始事件

注意：当刚刚开始滑动时，event.nativeEvent.contentOffset 仍然是上次滑动数据

```js
onScrollBeginDrag(event);
```

#### Params

|       | 类型 | 描述 |
| ----- | ---- | ---- |
| event | -    | -    |

### 重置到某个 Tab

```js
resetToPage(pageNum);
```

#### Params

|         | 类型  | 描述 |
| ------- | ----- | ---- |
| pageNum | mixed | -    |

### 滚动到第几页

```js
scrollToPage(pageNum);
```

#### Params

|         | 类型  | 描述 |
| ------- | ----- | ---- |
| pageNum | mixed | -    |

### TopBar

```js
renderTopBar();
```

#### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |
