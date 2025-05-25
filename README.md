# AI API 调用演示页面

这是一个轻量级的、响应式设计的API调用演示页面，可以在各种设备上运行。该网页支持调用任何符合RESTful规范的AI API 接口。

## 功能特点

- 响应式布局：适配手机、平板和桌面设备
- 输入验证：提供清晰的输入提示信息
- 支持身份验证：可配置API密钥
- 实时响应展示：格式化显示API响应结果
- 完全静态：无需服务器即可运行

## 使用方法

1. 将整个`dh-ai`文件夹部署到你的Web服务器
2. 在浏览器中打开`index.html`
3. 在表单中输入API地址、密钥（如果需要）和输入文本
4. 点击"发送请求"按钮查看结果

## 示例API（仅用于测试）

你可以使用以下测试API进行体验：

- **Echo API**（返回原始请求数据）: `https://jsonplaceholder.typicode.com/posts`
- **Text Analysis API**: `https://api.example.com/text-analysis` (示例地址)

## 技术细节

- 使用Bootstrap 5实现响应式设计
- 使用原生JavaScript Fetch API进行网络请求
- 包含友好的用户界面和错误处理
- 支持CORS跨域请求