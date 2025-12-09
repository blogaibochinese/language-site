1. **修改 CSS 布局**：创建一个容器来容纳两个支付按钮，使用 Flexbox 使其并列显示
2. **添加 Krak Pay 按钮**：复制 Binance Pay 按钮的结构，修改为 Krak Pay 样式
3. **创建 Krak Pay 模态框**：复制 Binance Pay 模态框的结构，修改内容为 Krak Pay 相关信息
4. **添加 JavaScript 函数**：实现 Krak Pay 模态框的显示、关闭和地址复制功能
5. **更新点击模态框外部关闭的逻辑**：确保点击模态框外部时能正确关闭 Krak Pay 模态框

具体修改点：

* 在 `.payment-section` 内添加一个 Flex 容器

* 将现有的 Binance Pay 按钮和新创建的 Krak Pay 按钮放入该容器

* 复制 `binanceModal` 结构，创建 `krakModal`

* 复制相关 JavaScript 函数，修改为 Krak Pay 版本

* 更新 CSS

