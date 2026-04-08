# 好了么 🌿

每天记一件小确幸，对抗焦虑。

---

## 如何上线（免费，5 分钟）

### 方案一：GitHub Pages（推荐）

1. 打开 https://github.com 新建仓库，名称填 `haoleme`，选 Public
2. 把 `index.html` 上传到仓库根目录
3. 进入 **Settings → Pages**，Source 选 `main` 分支、`/ (root)` 文件夹，点 **Save**
4. 等 2 分钟，网站地址就会出现：`https://你的用户名.github.io/haoleme`

### 方案二：Cloudflare Pages

1. 登录 https://dash.cloudflare.com
2. Workers & Pages → Create Application → Pages → Connect to Git
3. 连接 GitHub 仓库，部署 `index.html`
4. 得到免费域名地址

### 方案三：直接发给用户

双击 `index.html` 即可在浏览器中运行，所有数据存在本地。

---

## 功能说明

- **每日打卡**：每天记录一件小确幸
- **种子区**：种下你的焦虑种子，随时修改
- **木心年轮图**：打卡数据可视化成一圈圈年轮
- **星球动画**：小确幸化作星星围绕旋转
- **社区数据**：可以看到总浏览量、种种子人数、打卡总次数

---

## 技术说明

- 纯前端，无后端依赖
- 数据存储：localStorage（本地）+ countapi（全局统计）
- countapi 是免费公共服务，数据公开可见，适合公益项目冷启动
- 如需私有数据，请使用 Supabase / LeanCloud / Firebase 等替代

---

## 自定义修改

- 编辑 `index.html` 中的 `NS = 'haoleme'` 可更改 countapi 命名空间
- 样式在 `<style>` 标签内，变量定义在 `:root` 中

---

*这是一个公益项目，愿你在这里找到平静。*
