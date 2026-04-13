# 贡献指南

感谢您对Claw生态系统的兴趣！我们欢迎各种形式的贡献，无论是代码、文档、测试还是问题反馈。

## 🎯 贡献方式

### 1. 报告问题
- 使用GitHub Issues报告bug或提出功能建议
- 在报告前请先搜索是否已有类似问题
- 提供清晰的问题描述和复现步骤

### 2. 代码贡献
- Fork仓库并创建功能分支
- 遵循代码风格和规范
- 添加适当的测试用例
- 提交清晰的提交信息

### 3. 文档改进
- 修正拼写错误和语法问题
- 改进文档结构和可读性
- 添加示例代码和使用说明
- 翻译文档到其他语言

### 4. 测试贡献
- 添加单元测试和集成测试
- 提高测试覆盖率
- 报告测试中发现的问题
- 改进测试框架和工具

## 📝 开发流程

### 1. 准备工作
```bash
# 1. Fork仓库
# 2. 克隆到本地
git clone https://github.com/你的用户名/仓库名.git

# 3. 添加上游仓库
git remote add upstream https://github.com/nzq336699/仓库名.git

# 4. 创建功能分支
git checkout -b feature/你的功能名称
```

### 2. 开发工作
- 编写代码和文档
- 运行测试确保通过
- 遵循项目代码规范
- 保持提交历史清晰

### 3. 提交更改
```bash
# 1. 添加更改
git add .

# 2. 提交更改
git commit -m "描述你的更改"

# 3. 推送到你的仓库
git push origin feature/你的功能名称
```

### 4. 创建Pull Request
- 在GitHub上创建Pull Request
- 描述你的更改和目的
- 关联相关的问题（如果有）
- 等待代码审查和反馈

## 🧪 代码规范

### 代码风格
- 遵循项目的现有代码风格
- 使用有意义的变量和函数名
- 添加适当的注释和文档
- 保持代码简洁和可维护

### 提交规范
- 提交信息使用英文或中文
- 遵循约定式提交规范（Conventional Commits）
- 提交信息格式：`类型(范围): 描述`
- 常见类型：feat, fix, docs, style, refactor, test, chore

### 测试要求
- 新功能必须包含测试用例
- 修复bug时添加回归测试
- 保持测试代码的清晰和可维护
- 运行所有测试确保通过

## 🔧 开发环境

### 环境要求
- Node.js (版本要求见package.json)
- Python (如果需要)
- Git
- 代码编辑器（推荐VS Code）

### 安装依赖
```bash
# 安装项目依赖
npm install

# 或使用yarn
yarn install
```

### 运行测试
```bash
# 运行所有测试
npm test

# 运行特定测试
npm test -- 测试文件路径

# 查看测试覆盖率
npm run coverage
```

## 🤝 社区准则

### 行为准则
- 尊重所有社区成员
- 建设性的讨论和反馈
- 包容不同的观点和经验
- 遵守开源社区的行为准则

### 沟通渠道
- GitHub Issues - 问题反馈和功能讨论
- GitHub Discussions - 技术讨论和知识分享
- Pull Requests - 代码审查和合并
- 文档和注释 - 代码解释和使用说明

## 📚 学习资源

### 新手入门
- [项目README](README.md) - 项目概述和快速开始
- [开发文档](docs/development.md) - 详细开发指南
- [API文档](docs/api.md) - API参考和使用示例

### 进阶学习
- [架构设计](docs/architecture.md) - 系统架构和设计决策
- [最佳实践](docs/best-practices.md) - 开发最佳实践和模式
- [性能优化](docs/performance.md) - 性能优化技巧和建议

## 🙏 致谢

感谢所有为Claw生态系统做出贡献的开发者！您的每一份贡献都让这个项目变得更好。

如果您有任何问题或需要帮助，请随时通过GitHub Issues联系我们。

---

*让我们一起构建更好的AI助手生态系统！*