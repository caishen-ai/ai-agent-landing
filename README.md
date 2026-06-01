# AI Agent 工作流定制 - GitHub Pages 部署

## 一键部署到 GitHub Pages

```bash
# 1. 创建仓库
gh repo create ai-agent-landing --public --push --source=.

# 2. 开启 GitHub Pages
gh api repos/$(git config user.name)/ai-agent-landing/pages -X POST -f 'source[branch]=main' -f 'source[path]=/'

# 3. 等待30秒后访问
# https://<你的用户名>.github.io/ai-agent-landing/
```

## 需要做什么

1. GitHub Token 已就绪（如果老板之前创建过）
2. 部署后把链接发到掘金/知乎/dev.to 文章里
3. 客户通过页面留言 → 手动联系 → 确认需求 → 交付 → 收款

## 收款方式

- 微信转账（老板微信号收款）
- 支付宝转账
- 先交付后付款（零风险承诺）

## 成本

- GitHub Pages：¥0
- 域名：不需要（github.io 子域名免费）
- 扣子账号：免费注册
- 总计：¥0
