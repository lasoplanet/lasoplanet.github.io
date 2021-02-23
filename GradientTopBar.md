## `<GradientTopBar />`

### Props

| 属性                | 类型   | 默认值             | 必填 | 描述 |
| ------------------- | ------ | ------------------ | ---- | ---- |
| style               | object | null               | ❌   | -    |
| leftIcon            | object | <BlackBackImage /> | ❌   | -    |
| rightIcon           | object | null               | ❌   | -    |
| yOffset             | number | 0                  | ❌   | -    |
| title               | string | ''                 | ❌   | -    |
| yRange              | number | 200                | ❌   | -    |
| gradient            | bool   | true               | ❌   | -    |
| onLeftPress         | func   | null               | ❌   | -    |
| onRightPress        | func   | null               | ❌   | -    |
| rightBtnIcon        | bool   | false              | ❌   | -    |
| leftBtnStyle        | object | null               | ❌   | -    |
| rightBtnStyle       | object | null               | ❌   | -    |
| contentGradient     | bool   | true               | ❌   | -    |
| titleContainerStyle | object | null               | ❌   | -    |
| titleStyle          | object | null               | ❌   | -    |
| responsiveLeftView  | object | null               | ❌   | -    |

### Methods

- 隐藏

```js
hideTopBar(duration);
```

#### Params

|          | 类型 | 描述 |
| -------- | ---- | ---- |
| duration | -    | -    |

- 显示

```js
showTopBar(duration);
```

#### Params

|          | 类型 | 描述 |
| -------- | ---- | ---- |
| duration | -    | -    |
