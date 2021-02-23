## `<LSParabola />`

### Props

| 属性       | 类型                        | 默认值   | 必填 | 描述 |
| ---------- | --------------------------- | -------- | ---- | ---- |
| scale      | bool                        | false    | ❌   | -    |
| animateEnd | func                        | () => {} | ❌   | -    |
| curvature  | number                      | 0.003    | ❌   | -    |
| duration   | number                      | 350      | ❌   | -    |
| style      | object                      | null     | ❌   | -    |
| children   | PropTypes.object.isRequired | -        | ✅   | -    |

### Methods

- ref

```js
getRef();
```

### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |

- 获取 inputRange, outputX, outputY 运动轨迹

```js
getPaths(position);
```

#### Params

|          | 类型  | 描述 |
| -------- | ----- | ---- |
| position | mixed | -    |

### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |

- 开启动画

```js
run(position, data);
```

#### Params

|          | 类型 | 描述 |
| -------- | ---- | ---- |
| position | -    | -    |
| data     | -    | -    |
