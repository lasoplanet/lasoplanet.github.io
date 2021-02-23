## `<VideoPlayer />`

### Props

| 属性                         | 类型 | 默认值    | 必填 | 描述 |
| ---------------------------- | ---- | --------- | ---- | ---- |
| toggleResizeModeOnFullscreen | -    | true      | ❌   | -    |
| playInBackground             | -    | false     | ❌   | -    |
| playWhenInactive             | -    | false     | ❌   | -    |
| showOnStart                  | -    | true      | ❌   | -    |
| resizeMode                   | -    | 'contain' | ❌   | -    |
| paused                       | -    | false     | ❌   | -    |
| repeat                       | -    | false     | ❌   | -    |
| volume                       | -    | 1         | ❌   | -    |
| muted                        | -    | false     | ❌   | -    |
| rate                         | -    | 1         | ❌   | -    |

### Methods

- 可开启 Loading 动画

```js
loadAnimation();
```

- 隐藏控制器

```js
_hideControls();
```

- 切换控制器显示状态

```js
_toggleControls();
```

- 切换播放状态

```js
_togglePlayPause();
```

- 计算视频时间

```js
calculateTime(time);
```

#### Params

|      | 类型 | 描述 |
| ---- | ---- | ---- |
| time | -    | -    |

### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |

- 格式化视频时间

```js
formatTime(time);
```

#### Params

|      | 类型 | 描述 |
| ---- | ---- | ---- |
| time | -    | -    |

- 快进

```js
seekTo(time);
```

#### Params

|      | 类型 | 描述 |
| ---- | ---- | ---- |
| time | -    | -    |

- 控制按钮

```js
renderControl(children, callback, style);
```

#### Params

|          | 类型  | 描述 |
| -------- | ----- | ---- |
| children | mixed | -    |
| callback | mixed | -    |
| style    | -     | -    |

- 空视图

```js
renderNullControl();
```

### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |

- 顶部控制器

```js
renderBottomControls();
```

### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |

- 快进 SeekBar

```js
renderSeekbar();
```

### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |

- 播放/暂停 按钮

```js
renderPlayPause();
```

### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |

- 视频时间

```js
renderTimer();
```

### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |

- Loading

```js
renderLoader();
```

### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |

- 加载错误提示

```js
renderError();
```

### return

| 类型 | 描述 |
| ---- | ---- |
|      |      |
