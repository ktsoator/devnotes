# DevNotes 📚

<div align="right">

**语言切换 / Languages**: [English](README.md) | [简体中文](README.zh-CN.md)

</div>

> 个人技术学习笔记、经验总结与代码示例仓库

这是一个系统化的技术知识库，用于记录学习过程中的笔记、原理图、实践经验和代码示例。

## 📁 目录结构

```
.
├── .templates/          # 笔记模板
├── archives/            # 绘图源文件
├── assets/              # 静态资源
│   ├── diagrams/        # 原理图
│   └── images/          # 其他图片
├── topics/              # 核心知识区
│   ├── cs/              # 计算机基础
│   │   ├── network/     # 网络
│   │   ├── os/          # 操作系统
│   │   └── dsa/         # 数据结构与算法
│   ├── web/             # Web 综合技术
│   │   ├── frontend/    # 前端
│   │   └── backend/     # 后端
│   └── devops/          # 工具与部署
├── playground/          # 简单示例
├── projects/            # 完整项目
└── README.md            # 本文件
```

---

## 📖 目录说明

### `.templates/` - 笔记模板

存放各种 Markdown 笔记模板，用于快速创建统一格式的文档。

**示例模板**：
- `topic.md` - 知识点笔记模板
- `demo.md` - 代码示例模板
- `project.md` - 项目说明模板

---

### `archives/` - 绘图源文件

存放可编辑的绘图源文件，用于后续修改和版本管理。

**支持的格式**：
- `.excalidraw` - Excalidraw 绘图文件
- `.fig` - Figma 设计文件
- `.drawio` - Draw.io 图表文件
- `.sketch` - Sketch 设计文件

---

### `assets/` - 静态资源

存放笔记中引用的所有静态资源文件。

#### `assets/diagrams/` - 原理图
- 存放从绘图源文件导出的 **PNG/SVG** 格式的知识点原理图
- 用于在 Markdown 笔记中引用
- 文件命名规范：`<主题>-<具体内容>.png/svg`
  - 示例：`cors-preflight-flow.png`

#### `assets/images/` - 其他图片
- 存放截图、配图、图标等其他类型的图片资源
- 用于美化文档或作为示例

---

### `topics/` - 核心知识区

技术知识笔记的主要存放区域，按照知识领域分类。

#### `topics/cs/` - 计算机基础 (Computer Science)

##### `network/` - 计算机网络
- HTTP/HTTPS 协议
- TCP/UDP
- **跨域问题 (CORS)**
- WebSocket
- DNS 解析
- 网络安全

##### `os/` - 操作系统
- 进程与线程
- 内存管理
- 文件系统
- I/O 模型
- 并发与同步

##### `dsa/` - 数据结构与算法
- 常见数据结构（数组、链表、树、图等）
- 经典算法（排序、搜索、动态规划等）
- 算法题解
- 时间复杂度分析

---

#### `topics/web/` - Web 综合技术

##### `frontend/` - 前端开发
- HTML/CSS/JavaScript
- 框架与库（React、Vue、Svelte 等）
- 前端工程化
- 浏览器原理
- 性能优化
- 前端安全

##### `backend/` - 后端开发
- 编程语言（Go、Node.js、Python 等）
- Web 框架
- 数据库（SQL/NoSQL）
- API 设计
- 认证与授权
- 中间件配置

---

#### `topics/devops/` - 工具与部署

- **版本控制**：Git、GitHub 工作流
- **容器化**：Docker、Kubernetes
- **CI/CD**：自动化部署流程
- **Linux**：常用命令、Shell 脚本
- **监控与日志**：日志收集、性能监控
- **云服务**：AWS、GCP、阿里云等

---

### `playground/` - 简单示例

存放各种实验性的、简单的代码示例（Demo）。

**特点**：
- 单文件或少量文件
- 用于快速验证某个技术点
- 代码简洁，重点突出

**示例**：
```
playground/
├── cors-demo/
│   ├── server.go        # 简单的 CORS 服务端
│   └── index.html       # 测试页面
├── websocket-chat/
└── react-hooks-demo/
```

---

### `projects/` - 完整项目

存放结构完整、功能较为复杂的实践项目。

**特点**：
- 完整的项目结构
- 完善的文档和 README
- 可独立运行和部署
- 包含测试和配置

**示例**：
```
projects/
├── blog-system/
│   ├── frontend/
│   ├── backend/
│   └── README.md
└── task-manager/
```

---