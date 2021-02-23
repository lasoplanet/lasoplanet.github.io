# `<WechatAuthDialog />`

> 组件路径：`/App/Components/Common/Widgets/WechatAuthDialog/index.js`

# Props

| 属性             | 类型   | 默认值                                 | 必填 | 描述 |
| ---------------- | ------ | -------------------------------------- | ---- | ---- |
| prompt           | string | '绑定微信即可邀请好友助力快去绑定吧！' | ❌   | -    |
| cotainerStyle    | object | null                                   | ❌   | -    |
| onResultCallback | func   | null                                   | ❌   | -    |
| bindWechat       | func   | -                                      | ✅   | -    |
| checkBindWechat  | func   | -                                      | ✅   | -    |

## Methods

### 授权绑定

```js
onBindWechat();
```

### 检测微信是否绑定

```js
checkBindWechat(onSuccess, onFailure);
```

#### Params

|           | 类型 | 描述 |
| --------- | ---- | ---- |
| onSuccess | -    | -    |
| onFailure | -    | -    |

### 打开授权绑定 Dialog

```js
open();
```

### 关闭授权绑定 Dialog

```js
close();
```
