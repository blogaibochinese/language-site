### 任务分析
需要让 `top-tutors.html` 页面的 footer 和右侧悬浮搜索与 `spoken.html` 保持一致。通过对比两个文件，发现主要差异在于：
1. **Footer**：`spoken.html` 使用图片形式的社交媒体图标，而 `top-tutors.html` 使用 Font Awesome 图标
2. **搜索功能**：`spoken.html` 在顶部显示固定搜索栏，`top-tutors.html` 使用右侧悬浮按钮打开搜索弹窗

### 实现计划

#### 1. 更新 Footer
- 替换 `top-tutors.html` 中的现有 footer 为 `spoken.html` 中的 footer 内容
- 确保社交媒体链接、图片和版权信息完全一致

#### 2. 统一搜索功能
- 移除 `top-tutors.html` 中的悬浮搜索按钮和搜索弹窗
- 在 `top-tutors.html` 顶部添加与 `spoken.html` 相同的搜索容器
- 复制 `spoken.html` 中的 Pagefind 搜索 CSS 样式到 `top-tutors.html`
- 更新 Pagefind 初始化脚本以使用新的元素 ID

#### 3. 确保样式一致性
- 检查并确保所有相关 CSS 样式都已正确复制
- 验证页面布局在不同设备上的响应式表现

### 预期结果
- `top-tutors.html` 的 footer 将与 `spoken.html` 完全一致
- 搜索功能将从悬浮弹窗改为顶部固定搜索栏，与 `spoken.html` 保持一致
- 整体页面风格更加统一