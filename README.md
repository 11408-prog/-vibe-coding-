# -vibe-coding-
在尝试使用claude,codex等ai制作一个用于聊天和简单办公的agent，记录一些东西。

## 日志

## 一些问题和解决方法

### UI / 界面

**Q: 页面中边栏的代表 .exe 的图标始终删除不了**
A: 直接把整个栏隐藏即可。

### 窗口

**Q: 怎么使程序默认是全屏的**
A: 将 `w.show();` 换为 `w.showMaximized();`

### Git

**Q: 怎么提交 git 项目**
A:
```bash
git status                  # [1] 看状态
git diff --stat             # [2] 看改动量
git add 文件1 文件2 目录/    # [3] 暂存（用目录名代替 .）
git commit -m "说明"        # [4] 提交
```

### AI 模型 / Agent 配置

**Q: 使用 Ollama 下载的本地部署模型，调用时 url 输入什么**
A: 输入 `http://localhost:11434/v1`

**Q: 选择支持 Claude Code 的模型要注意什么**
A: 一定要能支持**工具调用**。

---

### 新增问题模板

复制下面这段，填好之后粘到对应主题下面（没有合适主题就新开一个 `##`）：

```markdown
**Q: 问题描述**
A: 解决方案
```



