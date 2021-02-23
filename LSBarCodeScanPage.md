## `<LSBarCodeScanPage />`

### Props

| 属性                      | 类型   | 默认值    | 必填 | 描述 |
| ------------------------- | ------ | --------- | ---- | ---- |
| navigation                | object | -         | ✅   | -    |
| onOpenSearch              | func   | () => { } | ❌   | -    |
| onOpenBind                | func   | () => { } | ❌   | -    |
| onOpenBarcodeDetail       | func   | () => { } | ❌   | -    |
| onMedicineBarCodeReceived | func   | () => { } | ❌   | -    |
| onBoxBarCodeReceived      | func   | () => { } | ❌   | -    |
| onCheckPhone              | func   | -         | ✅   | -    |

### Methods

- 返回

```js
goBack();
```

- 获取扫描结果

```js
barcodeReceived(event);
```

#### Params

|       | 类型  | 描述 |
| ----- | ----- | ---- |
| event | mixed | -    |

- Header 右边按钮单击事件

```js
topBarRightOnPress();
```

- Header 扫码界面底部按钮单击事件

```js
bottomDescOnPress();
```

- 切换闪光灯状态

```js
changeCameraFlashStatus();
```
