# 天狼星 · 学术助手

这是一个面向大学生写论文的学术助手网站，包含：

- 多引擎学术搜索
- 引用生成器
- 大学生论文工具箱
- 学术搜索网站评估榜单
- 浏览记录与本地账号
- 帧率模式设置
- 防火墙日志前端显示

## GitHub Pages 部署

1. 新建 GitHub 仓库。
2. 上传本文件夹里的全部文件。
3. 进入仓库 Settings → Pages。
4. Source 选择 Deploy from a branch。
5. Branch 选择 main，目录选择 /root。
6. 保存后等待 GitHub Pages 生成访问地址。

## 文件说明

- `index.html`：网站主页面，GitHub Pages 会默认识别它作为首页。
- `README.md`：项目说明。

注意：如果页面中调用了本地后端接口，例如 `http://localhost:3000`，GitHub Pages 不会运行 Node.js 后端。前端页面仍可打开，后端相关功能需要你在本地或服务器上单独运行后端。
