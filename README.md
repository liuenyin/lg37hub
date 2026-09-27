# ln's projects

温暖简约的个人项目聚合页。静态 HTML，无需构建依赖。

## 部署

在 Render 创建 Static Site 并连接本仓库：

- Build Command：`echo "Static site ready"`
- Publish Directory：`public`

也可使用 `render.yaml`。待临时地址确认可用后，将 `lg37.com` 和 `www.lg37.com` 从原 Math Duel 服务迁至本服务。Math Duel 已使用独立入口 `https://math.lg37.com`。

## 本地预览

在仓库根目录运行 `python -m http.server 4173 --directory public`，打开 http://localhost:4173。
请通过 HTTP 预览；Live2D 配置与模型不能通过 file:// 正常加载。

## 看板娘

组件在 `public/companion/`，支持点击问候、模型表情、视线跟随、拖动、键盘移动、收起与记忆偏好。手机默认收起，后台或减少动态效果模式暂停动画。

**当前未启用，也不包含角色模型。** 搜索到的三月七和花火常用模型禁止二次分发；长夜月尚未找到允许公开网页部署的授权。不能把他人的 GitHub 转载当成模型作者许可。

取得允许网页分发的模型后，按 `public/companion/README.md` 配置并重新验证。
