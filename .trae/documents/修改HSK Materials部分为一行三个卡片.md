1. 在CSS样式中添加一个新的.grid-3类，设置grid-template-columns为更小的minmax值，实现一行三个卡片
2. 将HSK Materials部分的grid-2类替换为grid-3类
3. 确保修改后的布局在不同屏幕尺寸下都能正常显示

具体修改：

* 在CSS中添加：
  .grid-3 {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 16px 32px;
  }

* 将第606行的<div class="grid-2">改为<div class="grid-3">

