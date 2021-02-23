# `<SmoothPinCodeInput />`

> 组件路径：`/App/Components/Common/Widgets/CodeInput/index.js`

# Props

| 属性             | 类型            | 默认值                         | 必填 | 描述 |
| ---------------- | --------------- | ------------------------------ | ---- | ---- |
| value            | string          | ''                             | ❌   | -    |
| codeLength       | number          | 4                              | ❌   | -    |
| cellSize         | number          | 48                             | ❌   | -    |
| cellSpacing      | number          | 4                              | ❌   | -    |
| placeholder      | string          | ''                             | ❌   | -    |
| mask             | string          | '\*'                           | ❌   | -    |
| password         | bool            | false                          | ❌   | -    |
| autoFocus        | bool            | false                          | ❌   | -    |
| containerStyle   | custom          | styles.containerDefault        | ❌   | -    |
| cellStyle        | custom          | styles.cellDefault             | ❌   | -    |
| cellStyleFocused | custom          | styles.cellFocusedDefault      | ❌   | -    |
| textStyle        | custom          | styles.textStyleDefault        | ❌   | -    |
| textStyleFocused | custom          | styles.textStyleFocusedDefault | ❌   | -    |
| animationFocused | string \ object | 'pulse'                        | ❌   | -    |
| onFulfill        | func            | -                              | ❌   | -    |
| onChangeText     | func            | -                              | ❌   | -    |
| onBackspace      | func            | -                              | ❌   | -    |
| keyboardType     | string          | 'numeric'                      | ❌   | -    |
