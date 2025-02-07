# 自然语言生成AI工作流

一个基于自然语言的智能工作流设计平台，支持通过自然语言描述快速构建和管理工作流。本项目采用现代化的前端技术栈和 AI 技术，提供直观的可视化界面和强大的自动化能力。

## 🌟 核心特性

### 自然语言工作流生成
- 🤖 支持通过自然语言描述自动生成完整工作流
- 📊 实时展示生成过程和中间结果
- 🔄 支持流式输出，提供更好的用户体验
- ✨ AI 智能补全节点配置

### 可视化工作流编辑
- 📐 直观的拖拽式节点编排
- 🔗 智能的连线和布局系统
- 🎨 美观的节点样式和动画效果
- 🛠 丰富的节点配置选项

### 节点类型支持
- 🌐 HTTP 请求节点：支持各种 HTTP 方法和参数配置
- 🔄 数据转换节点：支持数据映射、过滤和聚合
- 🤖 LLM 调用节点：集成 DeepSeek 等大语言模型
- 💾 数据库操作节点：支持查询和执行操作
- 📁 文件操作节点：支持文件读写和处理
- 📧 邮件节点：支持邮件发送和模板配置
- 🖼 图像处理节点：支持图片转换和处理
- ⏰ 调度器节点：支持定时和周期性任务
- 🔌 WebSocket 节点：支持实时通信
- 📨 消息队列节点：支持异步消息处理
- ➰ 循环节点：支持各类循环操作
- 🔀 并行节点：支持并发任务处理
- 🔄 聚合节点：支持多路结果合并

### 高级功能
- 📝 节点配置表单：直观的配置界面
- 🎯 条件分支：支持复杂的业务逻辑
- 📊 执行监控：实时查看执行状态
- 🔍 错误处理：完善的异常处理机制
- 🔄 自动布局：智能节点位置调整

## 🛠 技术栈

### 前端
- ⚛️ React + TypeScript
- 🎨 Ant Design 组件库
- 📊 React Flow 流程图引擎
- 🔄 状态管理：React Hooks
- 🌐 HTTP 客户端：Axios
- 🎯 工具库：Lodash

### 后端
- 🚀 FastAPI 框架
- 🗃 PostgreSQL 数据库
- 🤖 LangChain + DeepSeek
- 🔐 JWT 认证
- 📝 Pydantic 数据验证

### 开发工具
- 📦 Vite 构建工具
- 🔍 ESLint + Prettier 代码规范
- 🧪 Jest 单元测试
- 📝 TypeScript 类型检查

## 🚀 快速开始

1. 克隆项目
```bash
git clone https://github.com/yourusername/workflow-platform.git
cd workflow-platform
```

2. 安装依赖
```bash
# 后端依赖
pip install -r requirements.txt

# 前端依赖
cd frontend
npm install
```

3. 配置环境变量
```bash
cp .env.example .env
# 编辑 .env 文件，配置必要的环境变量
```

4. 启动服务
```bash
# 启动后端服务
uvicorn app.main:app --reload

# 启动前端开发服务器
npm run dev
```

5. 访问应用
```
http://localhost:3000
```

## 📚 使用指南

### 创建工作流
1. 在输入框中输入工作流描述
2. 点击"生成工作流"按钮
3. 等待 AI 生成工作流程图
4. 根据需要调整节点位置和配置

### 编辑节点
1. 双击节点打开配置面板
2. 修改节点配置
3. 点击保存应用更改

### 执行工作流
1. 配置完成后点击"执行"按钮
2. 在执行面板中查看进度
3. 查看执行结果和日志

## 🤝 贡献指南

欢迎提交 Pull Request 或提出 Issue。在提交代码前，请确保：

1. 代码符合项目规范
2. 通过所有测试
3. 更新相关文档
4. 添加必要的注释

## 📄 许可证

MIT

## 🙏 致谢

- [React Flow](https://reactflow.dev/)
- [Ant Design](https://ant.design/)
- [FastAPI](https://fastapi.tiangolo.com/)
- [LangChain](https://langchain.org/)
- [DeepSeek](https://deepseek.com/) 
