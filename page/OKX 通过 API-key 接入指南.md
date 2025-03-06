# OKX 通过 API-key 接入指南

## 连接 OKX
Finandy 服务允许您通过免费 API-key 实现与 [OKX](https://bit.ly/OKXe) 交易平台的安全连接。以下步骤帮助您快速完成 API 对接：

1. 注册 OKX，使用链接 [OKX](https://bit.ly/OKXe) （注意：邀请码已更新为 8265080）。
2. 将资金存入您的 [OKX](https://bit.ly/OKXe) 账户。
3. 进入期货交易页面，点击“更新交易”，并在弹窗中点击“切换”按钮。
4. 登录 Finandy 账户，进入“账户 → API Keys”页面。
5. 点击 **“连接 OKX”** 按钮。
6. 系统会显示快速 API 创建菜单。
7. 连接成功后，系统自动返回 Finandy 服务页面，并显示连接时创建的 API-key。

## 可能的错误
当创建 API-key 时，可能会遇到下列错误提示：

**Processing API key creation Error: OKX API error: Fast API is allowed to create only one API KEY**

此错误表示您之前已连接过 Finandy 服务。解决方法如下：

1. 登录您的 [OKX](https://bit.ly/OKXe) 账户，进入“账户 → API”页面。
2. 点击 **删除** 按钮，清除所有 API-key后重新尝试连接。

## 删除 API-key
若需删除 OKX 的 API-key，请按以下步骤操作：

1. 在 Finandy 网站的“账户 → API Keys”页面，点击 **删除** 按钮。
2. 注意：若打算在 OKX 平台删除 API-key，请务必同时在 Finandy 终端中删除相应的 API-key。

## 常见问题
### 1. 账户邀请码问题
对于之前创建账户时未使用或使用了不同邀请码的情况，没有额外限制或附加条件，该类账户均可正常使用。

### 2. 同时使用第三方服务会冲突吗？
使用 OKX API 接入第三方服务时可能会发生冲突，此类操作风险完全由用户自行承担。

### 3. 可否同时在 OKX、Binance 和 Finandy 平台交易？
可以，用户可以同时在这三个平台进行交易操作。

### 4. 连接 OKX 是否安全？
连接后生成的 API-key 仅允许我们服务器的 IP 访问。该过程与在 OKX 平台手动创建 API-key 的步骤相同，并且 Finandy 终端会对 API-key 进行加密存储。

如有疑问，欢迎加入我们的 Telegram chat 获取帮助。