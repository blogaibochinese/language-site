### 问题分析
当前HSK课程卡片在移动端（max-width: 768px）使用了`grid-template-columns: 1fr`，导致一行只显示一个卡片。

### 优化方案
1. **修改网格布局**：将移动端媒体查询中的`grid-template-columns`从`1fr`改为`repeat(2, 1fr)`，确保一行显示两个卡片
2. **调整间距**：保持适当的卡片间距，确保在各种手机宽度下都能正常显示
3. **优化卡片内边距**：确保卡片内容在小屏幕上依然清晰可读

### 具体修改
```css
@media (max-width: 768px) {
    .hsk-grid {
        grid-template-columns: repeat(2, 1fr); /* 修改为一行两列 */
        gap: 20px;
        padding: 15px;
    }
    /* 其他样式保持不变 */
}
```

### 预期效果
- 无论手机宽度如何，移动端一行始终显示两个HSK课程卡片
- 卡片间距适中，内容清晰可读
- 响应式布局保持良好的视觉效果