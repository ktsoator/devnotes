# DevNotes 📚

<div align="right">

**Languages**: [English](README.md) | [简体中文](README.zh-CN.md)

</div>

> Personal technical learning notes, experience summaries, and code examples repository

A systematic knowledge base for recording notes, diagrams, practical experience, and code examples during the learning process.

## 📁 Directory Structure

```
.
├── .templates/          # Note templates
├── archives/            # Drawing source files
├── assets/              # Static resources
│   ├── diagrams/        # Diagrams
│   └── images/          # Other images
├── topics/              # Core knowledge area
│   ├── cs/              # Computer Science fundamentals
│   │   ├── network/     # Networking
│   │   ├── os/          # Operating Systems
│   │   └── dsa/         # Data Structures & Algorithms
│   ├── web/             # Web technologies
│   │   ├── frontend/    # Frontend
│   │   └── backend/     # Backend
│   └── devops/          # Tools & Deployment
├── playground/          # Simple examples
├── projects/            # Complete projects
└── README.md            # This file
```

---

## 📖 Directory Description

### `.templates/` - Note Templates

Store various Markdown note templates for quickly creating documents with a unified format.

**Example Templates**:
- `topic.md` - Knowledge point note template
- `demo.md` - Code example template
- `project.md` - Project documentation template

---

### `archives/` - Drawing Source Files

Store editable drawing source files for future modifications and version control.

**Supported Formats**:
- `.excalidraw` - Excalidraw drawing files
- `.fig` - Figma design files
- `.drawio` - Draw.io diagram files
- `.sketch` - Sketch design files

---

### `assets/` - Static Resources

Store all static resource files referenced in notes.

#### `assets/diagrams/` - Diagrams
- Store **PNG/SVG** format knowledge point diagrams exported from drawing source files
- Used for referencing in Markdown notes
- Naming convention: `<topic>-<specific-content>.png/svg`
  - Example: `cors-preflight-flow.png`

#### `assets/images/` - Other Images
- Store screenshots, illustrations, icons, and other types of image resources
- Used to beautify documents or serve as examples

---

### `topics/` - Core Knowledge Area

The main storage area for technical knowledge notes, organized by knowledge domain.

#### `topics/cs/` - Computer Science Fundamentals

##### `network/` - Computer Networks
- HTTP/HTTPS protocol
- TCP/UDP
- **Cross-Origin Resource Sharing (CORS)**
- WebSocket
- DNS resolution
- Network security

##### `os/` - Operating Systems
- Processes and threads
- Memory management
- File systems
- I/O models
- Concurrency and synchronization

##### `dsa/` - Data Structures & Algorithms
- Common data structures (arrays, linked lists, trees, graphs, etc.)
- Classic algorithms (sorting, searching, dynamic programming, etc.)
- Algorithm solutions
- Time complexity analysis

---

#### `topics/web/` - Web Technologies

##### `frontend/` - Frontend Development
- HTML/CSS/JavaScript
- Frameworks and libraries (React, Vue, Svelte, etc.)
- Frontend engineering
- Browser internals
- Performance optimization
- Frontend security

##### `backend/` - Backend Development
- Programming languages (Go, Node.js, Python, etc.)
- Web frameworks
- Databases (SQL/NoSQL)
- API design
- Authentication and authorization
- Middleware configuration

---

#### `topics/devops/` - Tools & Deployment

- **Version Control**: Git, GitHub workflows
- **Containerization**: Docker, Kubernetes
- **CI/CD**: Automated deployment pipelines
- **Linux**: Common commands, Shell scripting
- **Monitoring & Logging**: Log collection, performance monitoring
- **Cloud Services**: AWS, GCP, Alibaba Cloud, etc.

---

### `playground/` - Simple Examples

Store various experimental, simple code examples (demos).

**Characteristics**:
- Single file or few files
- Used for quickly validating a technical point
- Concise code with clear focus

**Examples**:
```
playground/
├── cors-demo/
│   ├── server.go        # Simple CORS server
│   └── index.html       # Test page
├── websocket-chat/
└── react-hooks-demo/
```

---

### `projects/` - Complete Projects

Store structurally complete, functionally complex practical projects.

**Characteristics**:
- Complete project structure
- Comprehensive documentation and README
- Can run and deploy independently
- Includes tests and configurations

**Examples**:
```
projects/
├── blog-system/
│   ├── frontend/
│   ├── backend/
│   └── README.md
└── task-manager/
```

---

