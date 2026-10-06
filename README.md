### 👋 你好，我是 a2-DEL

一名专注 **AI Agent 工程化** 的全栈开发者。我最擅长的事：把大模型从"聊天框"变成"守规矩的数字员工"——每一个 AI 动作都有权限边界、有人审闸门、有审计留痕。

过去一年独立主导了 6 个从 0 到 1 的开源项目，覆盖 Web 全栈、企业级业务系统与 Windows 桌面工具，代码全部 MIT 开源。

**🛠 技术栈**

`Vue 3` `React 18 / 19` `Next.js` `TypeScript` `FastAPI` `Node.js` `PostgreSQL` `SQLite` `Dexie/IndexedDB` `PyQt6` `Docker` `Tailwind CSS`

**🧭 一条主线**：本地优先 / 数据不出端　+　岗位化 AI　+　人审与审计闭环

---

## 🔥 精选项目

### 🥇 企业级业务系统

**[冀慧学途 — 校园资助数智化协同平台](https://github.com/a2-DEL/jihui-xuetu)**
> 覆盖"学生申请 → 多级审批 → 银行放款 → 对账 → 审计"全链路的企业级业务操作系统。
>
> - 首创 **九维授权引擎**：角色 / 组织 / 数据范围 / 时间窗口 / 地理位置 / 工作流节点 / AI 风险等级 / 数据敏感度 / 操作类型，九维同时判定，任一不满足即拒绝
> - **17 类角色**专属工作台，身份证号、银行卡号按 P0–P5 分级自动脱敏
> - AI 助手"小海豚"对资金类操作**零写权限**，钱永远由人批
> - 90+ API 端点、193 个页面路由、38 个业务模块，Docker 一键启动 demo
>
> `Next.js 16` `React 19` `TypeScript` `Tailwind 4` `PostgreSQL` `Docker`

**[云财管家 — AI 全员业财协同系统](https://github.com/a2-DEL/yuncaiguanjia)**
> 纯前端、零后端、财务数据 100% 留存在浏览器本地的小微企业经营系统。
>
> - **6 个岗位隔离 AI 数字员工**：AI 只出 Proposal 待批提案，财务批准后才生成凭证——把财务内控的"不相容职务分离"原则写进代码
> - SHA-256 哈希审计链贯穿所有操作，本地可校验、不可篡改
> - 老板驾驶舱 / 财务工作台 / 业务快捷入口三套原生视图，PWA 可安装到手机桌面
> - 120+ 单元测试，TypeScript 零类型错误
>
> `React 18` `Dexie/IndexedDB` `Zustand` `Ant Design 5` `Recharts`

### 🥈 工程能力与产品差异化

**[PyLearn AI — 双轨编程实训平台](https://github.com/a2-DEL/pylearn-ai)**
> 面向高校 Python 教学，同时训练"独立写代码"与"指挥 AI 写代码"两种能力。
>
> - 双轨训练场：轨道 A 测试用例自动批改；轨道 B 五种 AI 协作模式（需求拆解 / Prompt 编程 / 企业面试真题 / 找 Bug 实战 / 结对编程）
> - **AI 协作依赖度仪表盘**：量化学生多大比例提交依赖 AI，防止"离不开 Copilot"
> - 插件化 AI 网关，新增模型厂商约 20 行适配器；无 API Key 自动降级 Mock，内网离线可用
>
> `FastAPI` `SQLAlchemy 2 async` `Vue 3` `Monaco Editor` `ECharts`

**[磁盘文件检视工具 — Windows 本地磁盘治理](https://github.com/a2-DEL/disk-inspector)**
> 面向电脑小白的桌面工具：只读扫描 + 风险翻译 + 受控删除，默认一个文件都不碰。
>
> - 六项稳定性根治：显式栈迭代替代递归（扛住 12000 层超深目录不栈溢出）、`__slots__` 降内存、HTML 流式分块生成、全局异常兜底
> - 系统核心目录白名单**勾选框物理禁用**，"彻底删除"仍进安全回收箱可还原
> - 已打包为单文件 EXE，含集成测试、GUI 冒烟测试与打包产物自检
>
> `Python 3.13` `PyQt6` `ctypes / Win32 API` `PyInstaller`

### 🥉 更多开源项目

| 项目 | 一句话 | 技术栈 |
|---|---|---|
| [源智 HR](https://github.com/a2-DEL/yuanzhi-hr) | 1 调度 Agent + 6 主管 + 21 执行 Agent 的虚拟 HR 团队，微内核插件架构，四层权限 | `Vue 3` `FastAPI` `SQLite` |
| [数智星图 · 白泽 Agent OS](https://github.com/a2-DEL/shuzhi-campus) | 高校空间微治理多智能体系统：责任归属知识图谱 + 45 个智能体协同 + RLS / Outbox | `Next.js` `Node.js` `PostgreSQL` |

---

## 📬 联系

- GitHub：[@a2-DEL](https://github.com/a2-DEL)
- 方向：全栈开发 / AI 应用工程
