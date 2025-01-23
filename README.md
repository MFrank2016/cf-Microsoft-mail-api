**项目介绍:**

 ## 微软邮箱 API 客户端 - 基于 Cloudflare Workers 的 Web UI

 本项目是一个基于 Cloudflare Workers 的轻量级微软邮箱 API 客户端 Web 应用程序。它提供了一个简洁美观的用户界面，让您可以方便地通过网页访问和管理您的微软邮箱 (Outlook, Hotmail 等)。

 **主要功能:**

 *   **查看邮件:** 支持查看收件箱 (INBOX) 和垃圾邮件 (Junk) 文件夹中的最新邮件或全部邮件。
 *   **清空邮箱:** 支持一键清空收件箱或垃圾邮件文件夹。
 *   **账号管理:** 支持添加、删除和管理多个微软邮箱账号。
 *   **一键导入:** 支持通过特定格式的字符串快速导入账号信息 (邮箱, 客户端 ID, 刷新令牌)。
 *   **自动暗黑模式:**  根据用户的系统设置自动切换浅色或深色主题。
 *   **添加到主屏幕:** 支持将网站添加到 iOS 和 Android 设备的主屏幕，提供类似原生应用的体验。
 *   **Outlook 风格 UI:**  界面设计模仿了微软 Outlook 网页版的风格，提供熟悉且专业的视觉体验。

 **技术栈:**

 *   **Cloudflare Workers:** 作为无服务器 (Serverless) 平台，提供快速、可靠且可扩展的后端服务。
 *   **HTML, CSS, JavaScript:** 构建用户界面和交互逻辑。
 *   **KV Storage:** 使用 Cloudflare 的键值存储 (KV) 来存储和管理账号信息。

 **为什么选择本项目？**

 *   **快速部署:** 得益于 Cloudflare Workers 的强大功能，您可以轻松地将本项目部署到全球边缘网络，享受极快的访问速度。
 *   **无需服务器:**  无需维护任何服务器，降低了运维成本和复杂性。
 *   **安全可靠:**  Cloudflare Workers 提供了安全可靠的运行环境，保护您的数据安全。
 *   **美观易用:**  直观的用户界面和丰富的功能，让您轻松管理您的微软邮箱。
 *   **开源免费:** 本项目完全开源，您可以自由地使用、修改和分享代码。

 **注意:**

 *   本项目是一个前端应用，通过调用您自己搭建的微软邮箱 API 来获取数据。您需要自行搭建后端 API 并配置 `API_BASE_URL`。
 *   API_BASE_URL默认为https://msoauth.unix.xin/ 您也可以自行部署，项目是https://github.com/HChaoHui/msOauth2api
 *   本项目使用 Cloudflare Workers 的 KV 存储来存储账号信息，您需要在部署前创建 KV 命名空间并将其绑定到 Worker。
 *   为了安全起见，请妥善保管您的账号信息，不要将其泄露给他人。

 **免责声明:**

 本项目仅供学习和参考，开发者不对任何因使用本项目而造成的损失负责。

 **在此感谢:**
 https://linux.do/t/topic/312720
 https://github.com/HChaoHui/msOauth2api

