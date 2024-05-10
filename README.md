# BootIMGExtractAction

**使用 Github Actions 来提取 Android Rom 内的 boot/init_boot 文件，并上传到 Github Releases**

## 🔧 使用

1. **创建**：
   - 点击 `Fork` 按钮，创建本项目的个人仓库

2. **配置**：
   - 在 Fork 后的仓库页面中，点击 `Actions` 选项
   - 选择 `extract_partition` 工作流
   - 根据提示选择你想要提取的文件，并确保正确填写了 ROM 的下载直链

3. **运行**：
   - 确认所有信息都已经正确填写后，点击 `Run workflow` 按钮开始运行

## 🚨 注意事项

- 如果在上传镜像时遇到 `Error 403: Resource not accessible by integration` 错误，请前往 `Settings` -> `Actions` -> `General` -> `Workflow permissions`，并将权限设置为`Read and write permissions`

## 🙏 感谢

- 特别感谢 [tosasitill](https://github.com/tosasitill) 和 [5ec1cff](https://github.com/5ec1cff)

- 本项目依赖于 [payload-dumper](https://github.com/5ec1cff/payload-dumper)

## 📜 许可证

本项目采用 [GPL-3.0 License](LICENSE)