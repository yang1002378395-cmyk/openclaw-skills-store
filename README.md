# OpenClaw Skills 商店

> 跳过繁琐配置，直接使用实战验证的 AI 技能包

## 🎯 项目目标

复制 **Claw Mart 模式**（$86k/月），专注中文市场，销售精选 AI 技能包。

## 📦 套餐定价

| 套餐 | 价格 | 包含 | 目标用户 |
|------|------|------|----------|
| 基础包 | ¥19 | 5 个入门 Skills | 新手 |
| 进阶包 | ¥49 | 8 个效率 Skills | 进阶用户 |
| 全套包 | ¥99 | 全部 20 个 Skills | 专业用户 |
| 定制服务 | ¥999 | 1 对 1 定制 + 技术支持 | 企业/团队 |

## 🚀 快速开始

### 1. 部署商店页面

```bash
cd ~/.openclaw/workspace/skills-store

# 方式 1: GitHub Pages（推荐）
# 1. 创建 GitHub 仓库 openclaw-skills-store
# 2. git init && git add . && git commit -m "Initial commit"
# 3. git remote add origin https://github.com/你的用户名/openclaw-skills-store.git
# 4. git push -u origin main
# 5. 在仓库 Settings > Pages > 选择 main 分支
# 6. 访问 https://你的用户名.github.io/openclaw-skills-store/

# 方式 2: 本地预览
open index.html
```

### 2. 添加收款码

编辑 `index.html`，找到收款码占位部分，替换为实际图片：

```html
<!-- 替换为实际收款码 -->
<img src="wechat-pay.jpg" alt="微信收款码" style="width: 200px;">
<img src="alipay.jpg" alt="支付宝收款码" style="width: 200px;">
```

### 3. 添加联系方式

在 `index.html` 中更新联系信息：

```html
<p>📧 Email: your@email.com</p>
<p>💬 Telegram: @your_username</p>
<p>💬 微信: your_wechat_id</p>
```

## 📊 收益预测

### 保守估计（月）
- 基础包：50 × ¥19 = ¥950
- 进阶包：30 × ¥49 = ¥1,470
- 全套包：20 × ¥99 = ¥1,980
- 定制：5 × ¥999 = ¥4,995
- **总计：¥9,395**

### 乐观估计（月）
- 基础包：200 × ¥19 = ¥3,800
- 进阶包：100 × ¥49 = ¥4,900
- 全套包：50 × ¥99 = ¥4,950
- 定制：10 × ¥999 = ¥9,990
- **总计：¥23,640**

## 🎯 推广渠道

1. **掘金** - 技术用户（已完成 94 篇文章）
2. **V2EX** - 开发者（模板已准备）
3. **知乎** - 内容创作者
4. **Discord/Telegram** - 海外中文用户
5. **朋友圈/微信群** - 私域流量

## 📋 待办事项

- [ ] 添加微信/支付宝收款码图片
- [ ] 添加联系方式（Email/Telegram/微信）
- [ ] 部署到 GitHub Pages
- [ ] 准备推广文案
- [ ] 建立自动化支付流程（可选）

## 🔗 相关文件

- 精选 Skills 列表：`~/.openclaw/workspace/memory/skills-packaging.md`
- Claw Mart 模式分析：`~/.openclaw/workspace/memory/clawmart-model.md`
- 推广模板：`~/.openclaw/workspace/memory/reddit-promo.md`, `v2ex-promo.md`

## 📚 参考竞品

- **Claw Mart** - $86k/月，卖 AI 配置包（英文）
- **OpenClaw Pro** - $52k/月，开发者工具包
- **setupclaw** - $43k/月，安装服务

---

创建：2026-03-13 01:05 AM
