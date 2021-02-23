# `<CountDownTimer />`

> 组件路径：`/App/Components/Common/Widgets/CountDownTimer/index.js`

# Props

| 属性            | 类型   | 默认值 | 必填 | 描述 |
| --------------- | ------ | ------ | ---- | ---- |
| time            | number | -      | ✅   | -    |
| timeOver        | func   | null   | ❌   | -    |
| showMillisecond | bool   | false  | ❌   | -    |
| markFontStyle   | object | null   | ❌   | -    |
| timeFontStyle   | object | null   | ❌   | -    |
| reStartTimer    | bool   | false  | ❌   | -    |
| timerStyle      | object | null   | ❌   | -    |
| containerStyle  | object | null   | ❌   | -    |
| showSeconds     | bool   | true   | ❌   | -    |
| hourMinuteOver  | bool   | false  | ❌   | -    |

## Methods

### 重置时间

```js
resetTimer();
```

### 时间初始化

```js
initTimer();
```

#### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |

### 天

```js
renderDay(info, index);
```

#### Params

|       | 类型 | 描述 |
| ----- | ---- | ---- |
| info  | -    | -    |
| index | -    | -    |

#### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |

### 时分秒

```js
renderTime(showMillisecond, info, index);
```

#### Params

|                 | 类型 | 描述 |
| --------------- | ---- | ---- |
| showMillisecond | -    | -    |
| info            | -    | -    |
| index           | -    | -    |

#### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |
