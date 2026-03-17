# 桂林村宣传网页

## 🚀 快速部署到 Netlify（推荐）

### 方式一：拖拽部署（30秒）

1. 访问：https://app.netlify.com/drop
2. 压缩 `桂林村宣传网页` 文件夹为 zip
3. 把 zip 文件拖拽到网页上
4. 立即获得网站链接！

### 方式二：GitHub 部署

1. 在 GitHub 创建仓库 `guilin-village`
2. 上传 `index.html` 文件
3. 访问：https://app.netlify.com/
4. 点击 "Add new site" → "Import an existing project"
5. 选择 GitHub 仓库，一键部署

### 方式三：命令行部署

```bash
# 安装 Netlify CLI
npm install -g netlify-cli

# 进入项目目录
cd 桂林村宣传网页

# 部署
netlify deploy --prod --dir=.
```

---

## 📁 文件说明

- `index.html` - 主网页文件
- `.github/workflows/deploy.yml` - GitHub Actions 自动部署配置

## 🌐 部署后网址

- Netlify: `https://xxx.netlify.app`
- GitHub Pages: `https://用户名.github.io/guilin-village/`

---

**制作时间**: 2026-03-17  
**制作者**: 小奇 🦞
