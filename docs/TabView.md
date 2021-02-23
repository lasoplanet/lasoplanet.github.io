# `<TabView />`

> 组件路径：`/App/Components/Common/Widgets/HeadTabView/TabView.js`

# Props

| 属性            | 类型 | 默认值 | 必填 | 描述 |
| --------------- | ---- | ------ | ---- | ---- |
| tabs            | -    | []     | ❌   | -    |
| initialPage     | -    | 0      | ❌   | -    |
| preInitSceneNum | -    | 0      | ❌   | -    |
| faultHeight     | -    | 2      | ❌   | -    |
| headerRespond   | -    | false  | ❌   | -    |
| frozeTop        | -    | 0      | ❌   | -    |

## Methods

### 计算 scrollValue

```js
handleScrollValue();
```

### 渲染 tabbar

```js
_renderTabBar();
```

### 渲染内容

```js
_renderContent();
```

### 获取标签子页面

```js
getScene();
```

### 跳转页面

```js
goToPage(index);
```

#### Params

|       | 类型 | 描述 |
| ----- | ---- | ---- |
| index | -    | -    |

### 动画停止

```js
onMomentumScrollEnd(e);
```

#### Params

|     | 类型 | 描述 |
| --- | ---- | ---- |
| e   | -    | -    |

### 显示页面发生变化

```js
pageHasChange(page);
```

#### Params

|      | 类型 | 描述 |
| ---- | ---- | ---- |
| page | -    | -    |

### 页面将要显示

```js
sceneWillShow(page);
```

#### Params

|      | 类型 | 描述 |
| ---- | ---- | ---- |
| page | -    | -    |

### tabbar 切换

```js
onChangeTab(currentIndex, page);
```

#### Params

|              | 类型 | 描述 |
| ------------ | ---- | ---- |
| currentIndex | -    | -    |
| page         | -    | -    |

### 整体的 layout 方法

```js
containerOnLayout(event);
```

#### Params

|       | 类型 | 描述 |
| ----- | ---- | ---- |
| event | -    | -    |

### 抛出内部子页面上下滑动的 y 动画对象

```js
makeScrollTrans();
```

### 标签页被拉拽

```js
scenePageDidDrag(index);
```

#### Params

|       | 类型   | 描述         |
| ----- | ------ | ------------ |
| index | number | 标签页的序号 |

### renderHeader 和 renderFooter 的参数装配

```js
makeParams();
```

### 组装子页面的参数

```js
makeSceneParams(item, index);
```

#### Params

|       | 类型 | 描述 |
| ----- | ---- | ---- |
| item  | -    | -    |
| index | -    | -    |

### 组装给 tabbar 的参数

```js
makeTabParams();
```
