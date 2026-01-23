## 问题分析

1. **瑞士银行账户未在前端显示**：瑞士银行账户信息已添加到 `bankAccounts` 对象中，但在 `country-links` 部分缺少对应的链接，导致用户无法访问。

2. **瑞士银行账户标题缺少国旗**：`bankAccounts.Switzerland.title` 使用了 "CH Switzerland" 而不是带有国旗 emoji 的格式，与其他国家不一致。

3. **国旗显示问题**：移动端显示国旗，桌面端显示国家代码，这可能是由于 emoji 字体渲染差异导致的，但主要问题是瑞士链接的缺失。

## 解决方案

1. **添加瑞士到国家链接**：在 `country-links` 部分添加瑞士链接，使用正确的国旗 emoji "🇨🇭"。

2. **修正瑞士银行账户标题**：将 `bankAccounts.Switzerland.title` 修改为 "🇨🇭 Switzerland 银行账户"，与其他国家保持一致。

3. **确保数据一致性**：确保 `data-country` 属性与 `bankAccounts` 对象中的键匹配。

## 具体修改步骤

1. **在国家链接部分添加瑞士**：

   * 在 `country-links` 容器中添加 `<a href="#" class="country-link" data-country="Switzerland">🇨🇭 Switzerland</a>`

2. **修正瑞士银行账户标题**：

   * 将 `bankAccounts.Switzerland.title` 从 "CH Switzerland 银行账户" 改为 "🇨🇭 Switzerland 银行账户"

3. **验证修改**：

   * 确认瑞士链接在前端显示

   * 确认瑞士银行账户详情弹窗显示正确的标题和国旗

   * 验证在不同设备上国旗显示正常

