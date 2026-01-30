# 🚀 前端工程师进阶学习计划 2026

> 目标：系统性梳理已有知识，填补知识盲区，紧跟技术发展趋势
> 
> 📅 **学习周期**：45 天（约 6.5 周）
> 
> ⏰ **每周学习时间**：≥ 20 小时
> 
> 📊 **总计学习时间**：约 130-150 小时

---

## 📋 学习计划概览

| 周次 | 模块 | 核心内容 | 时间分配 |
|------|------|---------|---------|
| 第 1 周 | 基础强化 | JS/TS 核心 + SCSS + 浏览器原理 | 20h |
| 第 2 周 | CSS 框架 | Tailwind v4 + shadcn/ui + 动画 | 20h |
| 第 3 周 | 框架深入 | Vue 3.5 + Nuxt 4 + React 19 | 20h |
| 第 4 周 | BFF 层 | Node.js + API 设计 + 认证授权 | 20h |
| 第 5 周 | AI 应用 | LLM + LangChain.js + RAG + Agent | 20h |
| 第 6 周 | 工程实践 | 构建工具 + 性能优化 + 项目实战 | 20h |
| 第 7 周 | 综合提升 | 架构设计 + 软技能 + 复盘总结 | 10h |

---

## ⏰ 每日时间分配建议

| 时间段 | 内容 | 时长 |
|--------|------|------|
| 学习时段 1 | 理论学习 + 文档阅读 | 1.5h |
| 学习时段 2 | 代码实践 + 项目练习 | 1.5h |
| 复习时段 | 笔记整理 + 知识回顾 | 0.5h |
| **工作日合计** | | **3.5h** |
| **周末合计** | 项目实战 + 深度学习 | **5h/天** |

---

## 📅 详细学习日程

### 第 1 周（Day 1-7）：基础强化

#### Day 1-2：JavaScript 核心
- [x] Event Loop 深入（宏任务/微任务/queueMicrotask）
- [x] 执行上下文与作用域链
- [x] 闭包原理与内存管理
- [x] 原型链与继承机制
- [x] this 绑定规则
- [ ] V8 引擎工作原理
- [ ] 垃圾回收机制（Mark-Sweep、Scavenge、增量标记）

#### Day 3-4：ES2024-2026 新特性
- [x] Proxy 与 Reflect 高级用法
- [x] Symbol 与 Iterator/Generator
- [x] async/await 与 Promise 原理
- [x] WeakMap/WeakSet 应用场景
- [ ] **ES2024+ 新特性**
  - Temporal API（日期时间处理）
  - Record & Tuple（不可变数据结构）
  - Pattern Matching（模式匹配）
  - Decorators（装饰器标准版）
  - Pipeline Operator（管道操作符）
  - Array Grouping / Promise.withResolvers()
  - AbortController 高级用法

#### Day 5：TypeScript 进阶
- [ ] 条件类型与 infer 关键字
- [ ] 模板字面量类型
- [ ] 递归类型与类型推导
- [ ] 类型守卫与 Narrowing
- [ ] 协变与逆变
- [ ] **TypeScript 5.x 新特性**
  - const 类型参数
  - satisfies 操作符
  - 装饰器标准化
  - using 声明（资源管理）
- [ ] 类型体操实战（type-challenges）
- [ ] 工具类型库（ts-toolbelt、type-fest）
- [ ] **JSON Schema 与数据校验**
  - JSON Schema 规范（Draft 2020-12）
  - AJV（Another JSON Validator）
    - 基础用法与配置
    - 自定义关键字
    - 自定义格式
    - 错误消息定制（ajv-errors）
    - 异步校验
  - JSON Schema 与 TypeScript 类型生成
    - json-schema-to-typescript
    - typescript-json-schema
  - 表单校验集成
  - API 请求/响应校验

#### Day 6：SCSS/Sass 深入
- [ ] 变量与作用域
- [ ] 嵌套规则与父选择器引用（&）
- [ ] Mixins 混入与参数
- [ ] 函数与运算
- [ ] 继承与占位符选择器（%placeholder）
- [ ] **模块化系统**
  - @use 与 @forward
  - 命名空间管理
  - 私有成员
- [ ] 条件语句与循环（@if/@for/@each）
- [ ] Maps 与 Lists 数据结构
- [ ] **7-1 架构模式**
  - abstracts/（变量、mixins、函数）
  - base/（重置、排版）
  - components/（按钮、卡片）
  - layout/（网格、头部、底部）
  - pages/（页面特定样式）
  - themes/（主题）
  - vendors/（第三方）

#### Day 7：浏览器与网络基础
- [ ] 渲染流程（Parse → Style → Layout → Paint → Composite）
- [ ] 重排与重绘优化
- [ ] 浏览器缓存策略（强缓存/协商缓存）
- [ ] **网络协议**
  - HTTP/2 多路复用
  - HTTP/3 (QUIC) 特性
  - WebSocket 与 SSE
  - WebRTC 基础
- [ ] 网络安全（CORS、CSP、XSS、CSRF）
- [ ] DNS 解析与 CDN 原理

---

### 第 2 周（Day 8-14）：CSS 框架与 UI 现代化

#### Day 8-9：CSS 现代特性
- [ ] CSS Container Queries（容器查询）
- [ ] CSS Subgrid
- [ ] CSS Layers (@layer)
- [ ] CSS Nesting（原生嵌套）
- [ ] **View Transitions API**（页面过渡动画）
- [ ] **Scroll-driven Animations**（滚动驱动动画）
- [ ] CSS Anchor Positioning（锚点定位）
- [ ] CSS :has() 选择器
- [ ] **Popover API**（原生弹出层）
- [ ] CSS @scope 规则
- [ ] CSS @starting-style
- [ ] color-mix() 颜色函数
- [ ] 逻辑属性（margin-inline 等）
- [ ] @property 自定义属性

#### Day 10-11：Tailwind CSS v4
- [ ] **Tailwind v4 核心变化**
  - 全新 Rust + Lightning CSS 引擎（构建速度提升 10x）
  - CSS-first 配置方式
  - 自动内容检测
  - 内置 CSS nesting 支持
  - @theme 指令
- [ ] 实用类（Utility Classes）体系
- [ ] 响应式设计与断点
- [ ] **暗色模式实现**
  - class 策略
  - media 策略
  - 自定义切换
- [ ] 自定义配置（tailwind.config.js → CSS 变量）
- [ ] **新特性深入**
  - Container Queries 支持
  - color-mix() 集成
  - 3D transforms
  - 动态 spacing/colors
- [ ] 插件开发
- [ ] 与 Vite 深度集成

#### Day 12-13：shadcn/ui 完整学习
- [ ] **设计理念**
  - Copy-Paste 组件模式
  - 组件所有权
  - 零运行时依赖
- [ ] **与 Radix UI 的关系**
  - Radix Primitives 无样式组件
  - 可访问性（a11y）内置
- [ ] **CLI 工具使用**
  - npx shadcn@latest init
  - npx shadcn@latest add
  - shadcn create（新版本）
- [ ] **组件定制与主题化**
  - CSS 变量主题系统
  - 暗色模式配置
  - 自定义颜色方案
- [ ] **shadcn/ui v4 新特性**
  - Tailwind v4 支持
  - React 19 支持
  - Base UI 选项（替代 Radix）
  - data-slot 属性
  - Field / FieldGroup 新组件
- [ ] **shadcn-vue** 使用（Vue 生态）
- [ ] Registry 与 Blocks

#### Day 14：其他 UI 框架与动画
- [ ] **无样式组件库对比**
  - Radix UI
  - Headless UI
  - Ark UI
  - React Aria
- [ ] **Tailwind 组件库**
  - daisyUI
  - Flowbite
  - Preline
- [ ] **动画库实践**
  - Framer Motion（React）
  - Motion One（通用）
  - GSAP（GreenSock）
  - Auto Animate
  - Lottie 动画
  - anime.js

---

### 第 3 周（Day 15-21）：框架深入

#### Day 15-16：Vue 3.5+ 深入
- [ ] **响应式系统源码**
  - Proxy 实现原理
  - effect/track/trigger
  - ref vs reactive
- [ ] 虚拟 DOM 与 Diff 算法
- [ ] Compiler 编译原理
- [ ] **Vue 3.5 新特性**
  - defineModel（双向绑定简化）
  - Reactive Props Destructure
  - useTemplateRef
  - useId
  - Deferred Teleport
- [ ] **Vapor Mode**（实验性无虚拟 DOM 模式）
- [ ] VueUse 源码学习
- [ ] Pinia 状态管理深入
  - 模块化设计
  - 持久化插件
  - 订阅机制

#### Day 17-19：Nuxt 4 全面掌握
- [ ] **Nuxt 4 核心变化**
  - 新的 `app/` 目录结构
  - Nitro 3 渲染引擎
  - 默认兼容性日期
  - 更严格的 TypeScript 配置
- [ ] **数据获取新特性**
  - useFetch / useAsyncData 合并
  - 自动请求取消（AbortController）
  - 智能缓存与去重
  - reactive keys 支持
  - lazy loading 优化
- [ ] **混合渲染策略**
  - SSR（服务端渲染）
  - SSG（静态生成）
  - ISR（增量静态再生）
  - Edge Rendering
  - Streaming SSR
- [ ] **Nuxt 4.2 新特性**
  - 实验性 TypeScript 插件支持
  - 异步 handler 抽取（减少 39% bundle）
  - 开发环境错误处理提升
- [ ] Nuxt Layers（层级架构）
- [ ] Nuxt DevTools
- [ ] **Nuxt 生态模块**
  - Nuxt Content（内容管理）
  - Nuxt Image（图片优化）
  - Nuxt UI（官方组件库）
  - Nuxt Auth
  - Nuxt I18n

#### Day 20：React 19 与生态
- [ ] **React 19 新特性**
  - Actions（表单处理简化）
  - useOptimistic（乐观更新）
  - use() Hook（Promise/Context 读取）
  - Document Metadata（元数据管理）
  - Asset Loading（资源预加载）
  - Server Components 稳定版
- [ ] **React Compiler**（自动优化）
- [ ] Fiber 架构与调度原理
- [ ] Concurrent Mode 并发模式
- [ ] **状态管理对比**
  - Zustand（轻量级）
  - Jotai（原子化）
  - Valtio（代理模式）
  - TanStack Query（服务端状态）

#### Day 21：跨框架方案与全栈框架
- [ ] **Astro**（内容优先）
  - Islands Architecture
  - 零 JS 默认
  - 多框架支持
- [ ] **Solid.js**（细粒度响应式）
  - Signals 系统
  - 编译时优化
- [ ] **Svelte 5**（Runes 系统）
  - $state、$derived、$effect
  - 编译器优化
- [ ] **Qwik**（可恢复性）
  - Resumability 概念
  - 延迟加载策略
- [ ] **Next.js 15+**
  - App Router 深入
  - Server Actions
  - Partial Prerendering
- [ ] **Remix**（嵌套路由与数据加载）

---

### 第 4 周（Day 22-28）：BFF 层与 API 设计

#### Day 22-23：Node.js 进阶
- [ ] Node.js 事件循环（与浏览器差异）
- [ ] Stream 流处理
- [ ] Cluster 与 Worker Threads
- [ ] **Node.js 22+ 新特性**
  - 原生 TypeScript 支持
  - 内置测试运行器
  - 权限模型
  - WebSocket 客户端
- [ ] **Bun 运行时**
  - 内置打包器
  - SQLite 支持
  - 性能优势（启动速度、执行速度）
- [ ] **Deno 2.0**
  - 权限系统
  - npm 兼容
  - Fresh 框架

#### Day 24-25：服务端框架
- [ ] **Nest.js 企业级开发**
  - 依赖注入（IoC）
  - 模块化架构
  - 管道与拦截器
  - 守卫与中间件
  - GraphQL 集成
- [ ] **轻量级框架对比**
  - Fastify（高性能）
  - Hono（边缘计算友好）
  - Elysia（Bun 原生）
  - Nitro（Nuxt 服务引擎）
- [ ] **tRPC 端到端类型安全**
  - 类型推导
  - 与 React/Vue 集成

#### Day 26：API 设计
- [ ] **RESTful 最佳实践**
  - 资源命名规范
  - HTTP 方法语义
  - 状态码使用
  - 版本管理策略
  - HATEOAS
- [ ] **GraphQL 深入**
  - Schema 设计
  - Resolver 优化
  - DataLoader 解决 N+1
  - 订阅（Subscriptions）
  - Apollo Server / Yoga
- [ ] **其他 API 模式**
  - gRPC 与 Protocol Buffers
  - WebSocket API 设计
  - SSE 实时推送
  - OpenAPI / Swagger 文档

#### Day 27：认证与授权
- [ ] **JWT 原理与最佳实践**
  - Access Token / Refresh Token
  - Token 存储策略
  - 安全注意事项
- [ ] **OAuth 2.0 / OIDC**
  - 授权码流程
  - PKCE 扩展
  - 第三方登录集成
- [ ] 单点登录（SSO）
- [ ] RBAC / ABAC 权限模型
- [ ] **Passkey / WebAuthn**（无密码认证）
- [ ] Session vs Token 对比

#### Day 28：缓存与性能
- [ ] **HTTP 缓存策略**
  - Cache-Control
  - ETag / Last-Modified
  - 缓存穿透/击穿/雪崩
- [ ] **Redis 缓存模式**
  - 缓存读写策略
  - 分布式锁
  - 发布订阅
- [ ] CDN 缓存配置
- [ ] BFF 层缓存设计

---

### 第 5 周（Day 29-35）：AI 应用

#### Day 29：AI 基础认知
- [ ] **大语言模型（LLM）原理**
  - Transformer 架构
  - Attention 机制
  - Tokenization
- [ ] **Token 与上下文窗口**
  - Token 计算
  - 上下文长度限制
  - 长文本处理策略
- [ ] 模型能力边界认知
- [ ] 幻觉问题与解决方案
- [ ] 模型评估与选择

#### Day 30：Prompt Engineering
- [ ] **基础技巧**
  - 清晰指令
  - 角色设定
  - 格式要求
- [ ] **高级技巧**
  - Chain-of-Thought（思维链）
  - Few-shot Learning
  - Zero-shot Learning
  - Self-Consistency
- [ ] **Prompt 安全**
  - 注入攻击防护
  - 输出过滤
  - 敏感内容处理

#### Day 31-32：AI 开发框架
- [ ] **LangChain.js**
  - Chain 链式调用
  - Agent 代理
  - Memory 记忆系统
  - Tools 工具调用
  - Retrieval（检索）
- [ ] **Vercel AI SDK**
  - useChat / useCompletion
  - 流式响应处理
  - 多模型支持
  - Edge Runtime 支持
- [ ] **API 集成**
  - OpenAI API（GPT-4、GPT-4o）
  - Claude API（Anthropic）
  - 国产大模型
    - DeepSeek
    - 通义千问
    - 文心一言
    - 智谱 GLM
    - Moonshot（Kimi）

#### Day 33：RAG 与向量数据库
- [ ] **RAG 原理**
  - 检索增强生成流程
  - 文档切分策略
  - Embedding 模型选择
- [ ] **向量检索优化**
  - 相似度算法
  - 混合检索（向量 + 关键词）
  - 重排序（Reranking）
- [ ] **向量数据库**
  - Pinecone
  - Milvus
  - Chroma
  - Weaviate
  - Qdrant
  - pgvector
- [ ] 知识库构建实战

#### Day 34：AI Agent
- [ ] **Agent 架构设计**
  - ReAct 模式
  - Plan-and-Execute
  - 工具调用（Function Calling）
- [ ] **多 Agent 协作**
  - Agent 通信
  - 任务分解
  - 结果聚合
- [ ] **实际应用**
  - 智能客服
  - 代码助手
  - 自动化工作流

#### Day 35：本地部署与 AI 辅助开发
- [ ] **本地模型部署**
  - Ollama
  - LM Studio
  - vLLM 推理加速
- [ ] **模型优化**
  - 量化（GGUF、GPTQ）
  - LoRA 微调基础
- [ ] **AI 辅助开发工具**
  - Cursor 高效使用
    - Rules 配置
    - Context 管理
    - Agent 模式
  - GitHub Copilot
  - Codeium / Tabnine
- [ ] AI 驱动 UI 生成（ScreenCoder 等研究）

---

### 第 6 周（Day 36-42）：工程化与应用实践

#### Day 36：构建工具
- [ ] **Vite 6 深入**
  - 核心原理（ESM + esbuild）
  - 插件开发
  - Environment API
  - SSR 配置优化
- [ ] **Rust 构建工具**
  - Rspack
  - Farm
  - Turbopack
  - **Rolldown**（Vite 未来打包器）
- [ ] esbuild / swc 原理
- [ ] Bundle 分析与优化

#### Day 37：Monorepo 与工程化
- [ ] **pnpm workspace**
  - 配置与使用
  - 依赖提升
  - 发布流程
- [ ] **Turborepo**
  - 任务编排
  - 远程缓存
  - 增量构建
- [ ] **Nx**
  - 依赖图
  - 代码生成
  - 插件系统
- [ ] Changesets 版本管理
- [ ] **代码质量**
  - ESLint 深度配置
  - Prettier 格式化
  - Husky + lint-staged
  - Commitlint 提交规范

#### Day 38：性能优化
- [ ] **加载性能**
  - Core Web Vitals（LCP、FID、CLS、INP）
  - 代码分割与懒加载
  - 预加载与预获取
  - 图片优化（WebP、AVIF）
  - 字体优化
  - 首屏加载优化
- [ ] **运行时性能**
  - 虚拟列表
  - 防抖与节流
  - Web Workers
  - requestAnimationFrame
  - 内存泄漏排查
- [ ] Chrome DevTools 性能分析

#### Day 39：测试与监控
- [ ] **测试策略**
  - Vitest 单元测试
  - Playwright E2E 测试
  - 组件测试（Testing Library）
  - 视觉回归测试
- [ ] **监控系统**
  - Sentry 错误监控
  - 性能监控（Web Vitals）
  - 日志系统（Winston、Pino）
  - 用户行为分析

#### Day 40：可视化与动画
- [ ] **图表库**
  - ECharts 高级用法
  - AntV（G2、G6、L7）
  - Chart.js
- [ ] **数据可视化**
  - D3.js 深入
  - 大数据量渲染优化
- [ ] **3D 与 WebGL**
  - Three.js 基础
  - WebGPU 新特性
  - Spline（3D 设计工具）
- [ ] **Canvas**
  - Canvas API 深入
  - Fabric.js / Konva.js
  - PixiJS（2D 渲染）

#### Day 41：跨端与实时应用
- [ ] **桌面应用**
  - Electron 深入
  - Tauri（Rust 桌面应用）
- [ ] **移动端**
  - React Native
  - 小程序跨端（Taro、uni-app）
  - Capacitor
- [ ] **实时应用**
  - WebSocket 实时通信
  - Socket.io
  - **协同编辑**
    - CRDT（冲突无关复制数据类型）
    - OT（操作转换）
  - 实时数据同步

#### Day 42：富文本与文件处理
- [ ] **富文本编辑器**
  - 编辑器架构设计
  - Slate.js
  - ProseMirror / TipTap
  - Lexical
- [ ] **文件处理**
  - 分片上传
  - 断点续传
  - 文件预览（Office、PDF）
  - 图片处理（裁剪、压缩）
  - 导入导出（Excel、CSV）

---

### 第 7 周（Day 43-45）：综合提升与复盘

#### Day 43：设计模式与架构
- [ ] **设计模式**
  - 创建型（单例、工厂、建造者）
  - 结构型（代理、装饰器、适配器）
  - 行为型（观察者、策略、命令）
  - 前端常用模式（发布订阅、中介者）
- [ ] **架构设计**
  - 前端架构模式
  - 组件设计原则
  - 目录结构设计
  - 技术选型方法论

#### Day 44：微前端与新趋势
- [ ] **微前端**
  - Module Federation 2.0
  - qiankun / micro-app
  - 无界微前端
  - 样式隔离方案
- [ ] **新平台 API**
  - Baseline 浏览器支持规范
  - File System Access API
  - Web Bluetooth / NFC
- [ ] **WebAssembly**
  - WASM 基础
  - Rust → WASM
  - WASI 与边缘计算

#### Day 45：总结与规划
- [ ] **知识复盘**
  - 整理学习笔记
  - 总结知识图谱
  - 标记薄弱环节
- [ ] **项目输出**
  - 完成综合项目
  - 编写技术文档
  - 部署上线
- [ ] **后续规划**
  - 制定 3 个月深入计划
  - 选择专精方向
  - 开源贡献目标

---

## 🎯 综合项目建议

### 项目选择（任选其一或组合）

#### 1. AI 增强的 Dashboard
- 技术栈：Nuxt 4 + Tailwind v4 + shadcn-vue + LangChain.js
- 功能：数据可视化 + AI 问答 + 实时更新

#### 2. 协同文档编辑器
- 技术栈：Vue 3 + Lexical/TipTap + WebSocket + CRDT
- 功能：实时协作 + 富文本 + 版本历史

#### 3. 智能组件库
- 技术栈：React 19 + shadcn/ui + Storybook
- 功能：可复用组件 + 文档生成 + 主题定制

#### 4. 全栈 AI 应用
- 技术栈：Nuxt 4 + Nitro + RAG + 向量数据库
- 功能：知识库问答 + 文档检索 + 智能推荐

---

## 📚 最新学习资源

### 官方文档（必读）
| 技术 | 链接 | 重点内容 |
|------|------|---------|
| Vue 3.5 | [vuejs.org](https://vuejs.org/) | Composition API、新特性 |
| Nuxt 4 | [nuxt.com](https://nuxt.com/) | app/ 目录、数据获取 |
| React 19 | [react.dev](https://react.dev/) | Actions、Server Components |
| Tailwind v4 | [tailwindcss.com](https://tailwindcss.com/) | CSS-first 配置 |
| shadcn/ui | [ui.shadcn.com](https://ui.shadcn.com/) | 组件定制、Tailwind v4 支持 |
| TypeScript | [typescriptlang.org](https://www.typescriptlang.org/) | 5.x 新特性 |

### 技术博客
- [Nuxt 4 发布博客](https://nuxt.com/blog/v4) - 官方新特性介绍
- [Nuxt 4.2 更新](https://nuxt.com/blog/v4-2) - 数据获取优化
- [Tailwind v4 Alpha](https://tailwindcss.com/blog/tailwindcss-v4-alpha) - 新引擎介绍
- [shadcn/ui Changelog](https://ui.shadcn.com/docs/changelog) - 最新更新
- [Anthony Fu](https://antfu.me/) - Vue 生态
- [Dan Abramov](https://overreacted.io/) - React 深度
- [张鑫旭](https://www.zhangxinxu.com/) - CSS 专家

### 视频课程
- Frontend Masters（React、Vue 高级课程）
- Egghead.io（短小精悍的技术视频）
- YouTube - Fireship（快速技术概览）
- YouTube - Theo（前端趋势分析）
- 极客时间（中文深度课程）

### AI 学习资源
- [OpenAI 官方文档](https://platform.openai.com/docs)
- [LangChain.js 文档](https://js.langchain.com/)
- [Vercel AI SDK](https://sdk.vercel.ai/)
- [Prompt Engineering Guide](https://www.promptingguide.ai/)

### 开源项目学习
- Vue 3 源码
- Vite 源码
- VueUse 源码
- shadcn/ui 源码
- LangChain.js 源码

---

## 📊 进度追踪表

### 周进度

| 周次 | 计划内容 | 实际完成 | 完成度 | 备注 |
|------|---------|---------|--------|------|
| W1 | 基础强化 | | ⬜ 0% | |
| W2 | CSS 框架 | | ⬜ 0% | |
| W3 | 框架深入 | | ⬜ 0% | |
| W4 | BFF 层 | | ⬜ 0% | |
| W5 | AI 应用 | | ⬜ 0% | |
| W6 | 工程实践 | | ⬜ 0% | |
| W7 | 综合提升 | | ⬜ 0% | |

### 日打卡

```
Week 1: ⬜⬜⬜⬜⬜⬜⬜
Week 2: ⬜⬜⬜⬜⬜⬜⬜
Week 3: ⬜⬜⬜⬜⬜⬜⬜
Week 4: ⬜⬜⬜⬜⬜⬜⬜
Week 5: ⬜⬜⬜⬜⬜⬜⬜
Week 6: ⬜⬜⬜⬜⬜⬜⬜
Week 7: ⬜⬜⬜
```

---

## 📝 学习笔记模板

```markdown
# [知识点名称]

## 📅 学习日期
- YYYY-MM-DD

## 📌 核心概念
- 

## 🔍 深入理解
- 

## 💻 代码示例
```

```

## 🆚 对比分析
| 方案 | 优点 | 缺点 | 适用场景 |
|------|------|------|----------|
|      |      |      |          |

## ❓ 遇到的问题
- 

## 💡 解决方案
- 

## 🔗 参考资源
- 
```

---

## ✅ 学习检验标准

### 基础模块
- [ ] 能清晰解释 Event Loop 和异步机制
- [ ] 能手写常用 TypeScript 工具类型
- [ ] 能设计合理的 SCSS 架构

### 框架模块
- [ ] 能解释 Vue/React 响应式原理
- [ ] 能独立搭建 Nuxt 4 项目
- [ ] 能使用 shadcn/ui 构建 UI

### BFF 模块
- [ ] 能设计 RESTful API
- [ ] 能实现 JWT 认证流程
- [ ] 能配置合理的缓存策略

### AI 模块
- [ ] 能编写有效的 Prompt
- [ ] 能使用 LangChain.js 构建应用
- [ ] 能实现简单的 RAG 系统

### 工程化模块
- [ ] 能配置 Vite 构建优化
- [ ] 能进行性能问题排查
- [ ] 能搭建 CI/CD 流程

---

## 🎯 45 天后的目标

1. **知识体系**：建立完整的前端知识图谱
2. **实践能力**：完成 1-2 个综合项目
3. **技术输出**：整理 5+ 篇学习笔记
4. **持续学习**：制定后续 3 个月计划

---

> 💪 **学习箴言**：不要追求学完所有内容，而是要建立系统性的知识体系，遇到问题知道去哪里找答案。
> 
> 🌟 **核心原则**：理论 + 实践 + 输出 = 真正掌握
>
> 🚀 **持续迭代**：技术在变化，学习计划也要定期更新
>
> ⏰ **时间管理**：每天固定时间学习，保持节奏比突击更有效

---

