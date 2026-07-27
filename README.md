# 🎈 GitHub Issues 博客

基于 [Gwitter](https://github.com/SimonAKing/Gwitter) 构建的个人博客。

使用 GitHub Issues 作为后端，搭建一个轻量级的个人博客/微博客。

---

## 📝 使用说明

### 🚫 不要 Fork

**请勿直接 Fork 此仓库！**

Fork 会保留原始仓库的所有 Issues，无法正常使用。

### ✅ 正确方式

1. **克隆此仓库**（或点击 Use this template）
2. 创建你自己的 GitHub OAuth App
3. 修改 `src/config/index.ts` 中的配置：
   - `token`：你的 GitHub Personal Access Token
   - `clientID` / `clientSecret`：你的 OAuth App 凭证
   - `owner` / `repo`：你自己的仓库
4. 部署到 GitHub Pages

### ⚙️ 配置项

| 配置项 | 说明 |
|--------|------|
| `token` | GitHub Personal Access Token |
| `clientID` | OAuth App Client ID |
| `clientSecret` | OAuth App Client Secret |
| `owner` | GitHub 用户名 |
| `repo` | 仓库名称 |
| `onlyShowOwner` | 只显示本人帖子 |
| `enableEgg` | 开启彩蛋功能 |

---

## 🔗 原项目

[Gwitter by SimonAKing](https://github.com/SimonAKing/Gwitter)

> A lightweight microblogging platform powered by GitHub Issues

---

## 📄 License

MIT
