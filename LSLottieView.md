## `<LSLottieView />`

### Props

| 属性                        | 类型 | 默认值  | 必填 | 描述 |
| --------------------------- | ---- | ------- | ---- | ---- |
| source                      | -    | null    | ❌   | -    |
| speed                       | -    | 1       | ❌   | -    |
| onLayout                    | -    | null    | ❌   | -    |
| style                       | -    | null    | ❌   | -    |
| loop                        | -    | true    | ❌   | -    |
| autoPlay                    | -    | false   | ❌   | -    |
| progress                    | -    | null    | ❌   | -    |
| colorFilters                | -    | []      | ❌   | -    |
| autoSize                    | -    | true    | ❌   | -    |
| duration                    | -    | 2000    | ❌   | -    |
| resizeMode                  | -    | 'cover' | ❌   | -    |
| hardwareAccelerationAndroid | -    | true    | ❌   | -    |
| onAnimationFinish           | -    | null    | ❌   | -    |
| cacheStrategy               | -    | 'weak'  | ❌   | -    |

### Methods

- 播放动画

```js
play();
```

- 播放区间动画

```js
playSegments(startFrame, endFrame);
```

#### Params

|            | 类型  | 描述   |
| ---------- | ----- | ------ |
| startFrame | mixed | 开始帧 |
| endFrame   | mixed | 结束帧 |

- 使用 Animated 播放

```js
playForAnimated(endCallback);
```

#### Params

|             | 类型 | 描述 |
| ----------- | ---- | ---- |
| endCallback | -    | -    |

- 停止 Animated 播放

```js
stopForAnimated();
```

- 重置 Animated 进度

```js
resetForAnimated();
```

- 将动画进度重置为 0

```js
reset();
```

- 暂停动画

```js
pause();
```

- 恢复暂停的动画

```js
resume();
```
