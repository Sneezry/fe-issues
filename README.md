# FE Issues

## 安卓版本微信的内置浏览器无法更改`input[type=radio]`的尺寸

Solution: 在单选控件上覆盖一个`label`，控制`label`的尺寸

## iOS6和iOS7中canvas无法正确处理图片高度

Solution: http://stackoverflow.com/questions/11929099/html5-canvas-drawimage-ratio-bug-ios

## 安卓中，`text-align`属性`justify`值个别时候渲染有问题，尤其在行中用空格时，空格会被拉长

Solution: 尽量不用`justify`，对于标题、口号等必须两端对齐的地方用图片替换

## IE9不识别`application/json`MIME，会下载处理

Solution: 更改MIME
