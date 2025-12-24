# 统一 payments.html 导航栏样式

## 目标

将 payments.html 的导航栏样式替换为与 index.html 一致的样式，包括颜色、响应式设计和移动端导航。

## 分析

* index.html 有完整的导航栏样式（124-425行），包括彩色导航链接和响应式设计

* payments.html 目前使用自己的导航栏样式，与 index.html 不一致

* 两个文件的导航栏 HTML 结构基本相同，但 CSS 样式不同

## 计划步骤

1. **替换导航栏样式**：删除 payments.html 中现有的导航栏样式（29-130行），替换为 index.html 中的完整导航栏样式（124-425行）
2. **更新导航链接类**：将 payments.html 中的导航链接类更新为与 index.html 一致的彩色类（如 nav-link-red, nav-link-blue 等）
3. **统一移动端导航**：确保 payments.html 的移动端底部导航样式与 index.html 保持一致
4. **保留其他内容**：保持 payments.html 中的其他内容（支付方式相关的HTML、CSS和JS）不变

## 预期效果

* payments.html 的导航栏将与 index.html 完全一致

* 导航链接将显示相同的彩色样式

* 响应式设计和移动端导航将保持一致

* 支付页面的其他功能将不受影响

