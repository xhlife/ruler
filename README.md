# ruler
canvas标尺工具 (canvas ruler)

### 使用
```javascript
// x 轴
let row = Ruler.initRow({
  params
})
// y轴
let col = Ruler.initColumn({
  params
})
```
### 参数说明
* @colNum 刻度尺列数，如果传递了列数 > 0 将按份数画，非传统标尺
* @width 刻度尺宽度(px) Number
* @height 刻度尺高度(px) Number
* @startValue 开始的值 Number
* @background 刻度尺背景颜色 String
* @color 刻度线和字体的颜色 String
* @markColor  中心刻度标记颜色 String
* @startGap 标尺起点（与startValue值会叠加）

### return
初始化将返回一个canvas对象，可手动添加到目标对象上