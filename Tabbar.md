## `<Tabbar />`

### Props

| 属性               | 类型   | 默认值 | 必填 | 描述 |
| ------------------ | ------ | ------ | ---- | ---- |
| activeIndex        | number | -      | ✅   | -    |
| underLineHidden    | bool   | false  | ❌   | -    |
| style              | object | {}     | ❌   | -    |
| tabItemStyle       | custom | {}     | ❌   | -    |
| underlineStyle     | custom | {}     | ❌   | -    |
| renderTabItem      | func   | -      | ❌   | -    |
| scrollValue        | object | -      | ❌   | -    |
| tabSize            | array  | -      | ❌   | -    |
| renderLeftView     | func   | -      | ❌   | -    |
| renderRightView    | func   | -      | ❌   | -    |
| goToPage           | func   | -      | ❌   | -    |
| lineStyle          | custom | -      | ❌   | -    |
| tabsContainerStyle | -      | {}     | ❌   | -    |
| activeTextStyle    | -      | {      |

    fontSize: 14,
    color: '#4D4D4D',
    fontWeight: 'bold',

} | ❌ | - |
| inactiveTextStyle | - | {
fontSize: 14,
color: '#848484',
fontWeight: 'bold',

} | ❌ | - |
| tabs | - | [] | ❌ | - |
| averageTab | - | true | ❌ | - |

### Methods

- scrollview 是否需要滚动

```js
needsScrollTab();
```

- tabbar 的 scrollview 横着滚动多少

```js
toScrollTab(scrollX);
```

#### Params

|         | 类型 | 描述 |
| ------- | ---- | ---- |
| scrollX | -    | -    |

- 更新视图

```js
updateView(offset);
```

#### Params

|        | 类型 | 描述 |
| ------ | ---- | ---- |
| offset | -    | -    |

- 渲染 tabItem

```js
renderTabItem({ item, index, onLayoutTab });
```

#### Params

|                              | 类型 | 描述 |
| ---------------------------- | ---- | ---- |
| { item, index, onLayoutTab } | -    | -    |

- 渲染 tabbar 中间部分

```js
renderTabBar();
```

- 计算 tabItem 的样式

```js
makeTabStyle();
```

- 透明度 InputRange

```js
getInputRange();
```

- 透明度 outRange

```js
getOutRange(index);
```

#### Params

|       | 类型 | 描述 |
| ----- | ---- | ---- |
| index | -    | -    |

- 获取一个 tabItem 的宽度

```js
getItemWidth(index);
```

#### Params

|       | 类型 | 描述 |
| ----- | ---- | ---- |
| index | -    | -    |

- tabbar 的 layout 方法

```js
tabOnLayout(event);
```

#### Params

|       | 类型 | 描述 |
| ----- | ---- | ---- |
| event | -    | -    |
