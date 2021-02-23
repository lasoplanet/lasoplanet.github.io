# `<LSNumberPicker />`

> 组件路径：`/App/Components/Common/Widgets/LSNumberPicker.js`

# Props

| 属性                 | 类型   | 默认值                      | 必填 | 描述 |
| -------------------- | ------ | --------------------------- | ---- | ---- |
| editable             | bool   | true                        | ❌   | -    |
| inputStyle           | object | styles.inputStyle           | ❌   | -    |
| minNumber            | number | 1                           | ❌   | -    |
| maxNumber            | number | 10                          | ❌   | -    |
| leftBtn              | string | '-'                         | ❌   | -    |
| rightBtn             | string | '+'                         | ❌   | -    |
| placeholder          | string | ''                          | ❌   | -    |
| selectionColor       | string | '#eeeeee'                   | ❌   | -    |
| defaultValue         | number | 1                           | ❌   | -    |
| btnTextStyle         | object | null                        | ❌   | -    |
| leftBtnStyle         | object | null                        | ❌   | -    |
| rightBtnStyle        | object | null                        | ❌   | -    |
| inputContainerStyle  | object | null                        | ❌   | -    |
| leftBtnBorderStyle   | object | styles.leftBtnBorderStyle   | ❌   | -    |
| rightBtnBorderStyle  | object | styles.rightBtnBorderStyle  | ❌   | -    |
| containerBorderStyle | object | styles.containerBorderStyle | ❌   | -    |
| placeholderTextColor | string | '#eeeeee'                   | ❌   | -    |
| onChange             | func   | -                           | ✅   | -    |

## Methods

### 输入内容改变监听事件

```js
onChangeText(value);
```

#### Params

|       | 类型 | 描述 |
| ----- | ---- | ---- |
| value | -    | -    |

### 选择器状态改变

```js
numberPickerSelect(type);
```

#### Params

|      | 类型 | 描述 |
| ---- | ---- | ---- |
| type | -    | -    |
