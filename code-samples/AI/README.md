# AI 代码样例

本目录保留 AI 图片识别相关的 C# 后端样例代码。

## 包含文件

- `VisionController.cs`：图片识别 API 入口，包含食材识别、菜品识别和菜谱内容生成。
- `VisionService.cs`：AI 识别编排服务，包含图片校验、下载和 Provider 调用。
- `OpenAIVisionProvider.cs`：视觉模型调用与结果解析逻辑。

这些文件用于展示图片识别、结构化 JSON 输出、异常处理和 AI 服务封装方式。

公开版本不包含任何真实 API Key 或环境变量。
