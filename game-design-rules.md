# 游戏设计规则 (Game Design Rules)

## 技术标准

### 1. 技术栈
- **语言**: 纯 HTML5 + CSS3 + Vanilla JavaScript
- **框架**: 禁止使用任何框架 (React, Vue等)
- **依赖**: 无外部依赖，单文件部署
- **Canvas**: 使用 HTML5 Canvas 或纯DOM

### 2. 文件结构
```
public/games/[game-id]/
├── index.html      # 游戏主文件
└── (可选) assets/  # 静态资源
```

### 3. 响应式设计
- 移动端优先设计
- 触摸友好 (大按钮, 45px+ 触摸区域)
- 支持横屏/竖屏

### 4. 性能要求
- 首屏加载 < 2秒
- 动画流畅 60fps
- 内存占用 < 100MB

### 5. 无障碍设计
- 键盘可操作
- 高对比度
- 简洁UI

## UX标准

### 1. 儿童友好
- 大图标, 简单文字
- 明亮配色
- 即时反馈
- 无惩罚机制

### 2. 家长友好
- 无广告
- 无内购
- 无链接跳出
- 可自定义设置

### 3. 视觉风格
- 圆润边角
- 柔和阴影
- 童趣插画风格
- 统一配色方案

## 开发流程

1. 从 `development-queue.md` 选择下一个游戏
2. 创建分支: `git checkout -b feature/[game-id]`
3. 实现游戏
4. 注册到 `games-list.json`
5. 更新 `CHANGELOG.md`
6. 提交并合并到主分支
