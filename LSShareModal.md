## `<LSShareModal />`

### Props

| 属性          | 类型    | 默认值 | 必填 | 描述 |
| ------------- | ------- | ------ | ---- | ---- |
| miniInfo      | object  | null   | ❌   | -    |
| shareCallback | func    | null   | ❌   | -    |
| children      | element | -      | ✅   | -    |

### Methods

- 分享

```js
async onPressShare(shareTo)
```

#### Params

|         | 类型 | 描述 |
| ------- | ---- | ---- |
| shareTo | -    | -    |

- 下载分享图片

```js
onPressDownload();
```

- 注入 viewShotRef

```js
setViewShot(ref);
```

#### Params

|     | 类型  | 描述 |
| --- | ----- | ---- |
| ref | mixed | -    |

- 关闭 Modal

```js
closeModal();
```

- 打开 Modal

```js
openModal(ref, shareNetworkImg, getShareRef);
```

#### Params

|                 | 类型 | 描述 |
| --------------- | ---- | ---- |
| ref             | -    | -    |
| shareNetworkImg | -    | -    |
| getShareRef     | -    | -    |
