# `<LSShareDownloadPicker />`

> 组件路径：`/App/Components/Common/Widgets/LSShareDownloadPicker.js`

# Props

| 属性               | 类型 | 默认值 | 必填 | 描述 |
| ------------------ | ---- | ------ | ---- | ---- |
| isBlur             | -    | true   | ❌   | -    |
| animate            | -    | true   | ❌   | -    |
| isIOSScreenCapture | -    | false  | ❌   | -    |
| imageOnly          | -    | true   | ❌   | -    |

## Methods

### 分享给好友

```js
handleShareToSession();
```

### 分享到朋友圈

```js
handleShareToTimeline();
```

### 下载分享图片

```js
async handleDownLoad()
```

### 生成图片

```js
async generateShareImg(shareTo)
```

#### Params

|         | 类型 | 描述 |
| ------- | ---- | ---- |
| shareTo | -    | -    |
