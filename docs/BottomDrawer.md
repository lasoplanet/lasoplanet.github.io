# `<BottomDrawer />`

> 组件路径：`/App/Components/Common/Widgets/BottomDrawer/index.js`

底部抽屉 TODO

# Props

| 属性                             | 类型   | 默认值                                                                                                                 | 必填 | 描述 |
| -------------------------------- | ------ | ---------------------------------------------------------------------------------------------------------------------- | ---- | ---- |
| onExpanded                       | func   | () => {}                                                                                                               | ❌   | -    |
| borderRadius                     | number | 10                                                                                                                     | ❌   | -    |
| onModalOpened                    | func   | null                                                                                                                   | ❌   | -    |
| onModalClosed                    | func   | null                                                                                                                   | ❌   | -    |
| bottomSheetInitHeight            | number | 600                                                                                                                    | ❌   | -    |
| bottomSheetExpandHeight          | number | Device.isAndroid() ? '85%' : Device.isXSeriesDevice() ? Resolution.get().height _ 0.9 : Resolution.get().height _ 0.93 | ❌   | -    |
| showMask                         | bool   | true                                                                                                                   | ❌   | -    |
| initialSnap                      | number | 2                                                                                                                      | ❌   | -    |
| expandSnapIndex                  | number | 0                                                                                                                      | ❌   | -    |
| closeSnapIndex                   | number | 2                                                                                                                      | ❌   | -    |
| enabledGestureInteraction        | bool   | true                                                                                                                   | ❌   | -    |
| enabledContentGestureInteraction | bool   | true                                                                                                                   | ❌   | -    |

## Methods

### 打开抽屉

```js
open();
```

### 关闭抽屉

```js
close();
```
