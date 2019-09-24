# scratchcard
刮刮卡

## 使用方法

```
new ScratchCard({
    canvas: document.getElementById('canvas'),
    coverImg: 'scratch-2x.jpg',
    pixelRatio: 2,
    doneCallback: function() {
      console.log('done')
    }
});
```

| 参数 |  说明 | 默认 |
|:-----|------|-----:|
|canvas|canvas元素|null|
|showAllPercent|直接全部刮开的百分比|65|
|coverImg|图片图层|null|
|coverColor|纯色图层，例如：#cccccc。如果图片图层值不为null，则纯色图层无效|null|
|doneCallback|全部刮开回调|null|
|radius|屏幕倍数|20|
|pixelRatio|屏幕倍数|1|
|fadeOut|展现全部的淡出效果时间（ms）|2000|
