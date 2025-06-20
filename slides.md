---
# 您也可以简单地从"默认"开始
theme: seriph
# 来自 Anthony 精选 Unsplash 合集的随机图片
# 喜欢它们吗？请访问 https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# 关于您幻灯片的一些信息（支持 Markdown）
title: 欢迎来到 Cursor
info: |
  ## Cursor - AI 代码编辑器
  为数百万工程师打造的 AI 代码编辑器。

# 将 unocss 类应用于当前幻灯片
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# 幻灯片过渡：https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# 启用 MDC 语法：https://sli.dev/features/mdc
mdc: true
---

# Cursor - AI 编程助手

<div class="text-xl opacity-80">
  让编程更智能、更高效
</div>

<div class="mt-12 py-1" hover:bg="white op-10">
  按空格键继续 <carbon:arrow-right />
</div>

---

# 目录

<h4 style="margin: 0.5em 0;">1. Cursor是什么</h4>
<h4 style="margin: 0.5em 0;">2. Cursor界面长什么样子</h4>
<h4 style="margin: 0.5em 0;">3. Cursor怎么用</h4>
    <div style="color:#888;font-size:0.95em;margin-left:2em;">- Tab智能补全<br>- AI对话</div>
<h4 style="margin: 0.5em 0;">4. Cursor怎么用得更个性化</h4>
    <div style="color:#888;font-size:0.95em;margin-left:2em;">- 索引<br>- 规则<br>- MCP插件</div>

---

# 1. Cursor是什么

<div class="text-xl mt-6 mb-4 leading-loose">AI驱动的现代代码<span class="text-4xl font-black underline decoration-sky-500">编辑器IDE</
span></div>
<ul>
  <li class="text-lg mb-2">为开发者赋能，提升效率</li>
  <li class="text-lg mb-2">集成AI补全、对话、自动化等多种能力</li>
  <li class="text-lg mb-2">支持多种主流语言和框架</li>
</ul>

---

# 2. Cursor界面长什么样子

<div class="grid grid-cols-4 gap-4 h-fit place-content-center">

  <img class="col-span-3" src="./images/cursor-pic.png" />

<ul class="self-center ml-3">
  <li>文件树</li>
  <li>编辑区</li>
  <li>AI侧边栏</li>
  <li>状态栏与命令面板</li>
</ul>
</div>

---

# 3. Cursor怎么用？--核心功能概览

开始探索 Cursor 的 AI 功能：

<TabFeature />

---

# 3. 核心功能--Tab

<div class="flex items-start gap-x-6 text-left">
  <!-- Video Column -->
  <div class="w-4/5 rounded-xl overflow-hidden">
    <video src="https://mintlify.s3.us-west-1.amazonaws.com/cursor/images/cpp/cpp-full-video.mp4" autoplay loop playsinline muted class="w-full h-auto max-h-[50vh]"></video>
  </div>
  <!-- Text Column -->
  <div class="w-1/5 prose">
    <h3>快捷键指南</h3>
    <ul>
      <li><kbd>Tab</kbd> 接受建议</li>
      <li><kbd>Esc</kbd> 拒绝建议</li>
      <li><kbd>Ctrl</kbd>/<kbd>⌘</kbd> <kbd>→</kbd> 逐字接受</li>
    </ul>
  </div>
</div>

<div @click="$slidev.nav.go(2)" class="fixed bottom-4 left-4 inline-flex items-center justify-center px-3 py-1 border border-gray-300 text-gray-500 text-sm rounded-md hover:bg-gray-200 hover:text-gray-700 transition-colors duration-150 ease-in-out">
  <carbon:arrow-left class="inline-block" />
</div>

---

# Tab 高级功能 - 光标预测 (Cursor Prediction)

Cursor 不仅能补全代码，还能智能预测您在接受一次编辑后最可能需要跳转到的下一个代码位置。

<div class="grid grid-cols-7 gap-4 items-center">
  <div class="col-span-2">
    <ul>
      <li>自动预测下一个编辑位置</li>
      <li>连续编辑建议</li>
      <li>上下文感知的代码补全</li>
    </ul>
  </div>
  <div class="col-span-5 rounded-xl overflow-hidden flex justify-center">
    <img src="https://mintlify.s3.us-west-1.amazonaws.com/cursor/images/cpp/cp.png" class="w-full"/>
  </div>
</div>

---

# 核心功能--AI对话--Agent

AI 结对程序员，用于复杂的代码更改。

<div class="flex items-start gap-x-6 text-left">
  <!-- Video Column -->
  <div class="w-4/5 rounded-xl overflow-hidden">
    <video src="https://mintlify.s3.us-west-1.amazonaws.com/cursor/images/chat/overview.mp4" autoplay loop playsinline muted class="w-full h-auto max-h-[50vh]"></video>
  </div>
  <!-- Text Column -->
  <div class="w-1/5 prose gap-y-2 grid">
    <div>
      <h5>理解代码</h5>
      <div class="text-sm" style="color: #64748b;">询问有关不熟悉的代码的问题、获取解释或探索您的代码库</div>
    </div>
    <div>
      <h5>编辑代码</h5>
      <div class="text-sm" style="color: #64748b;">无需手动浏览文件即可进行调整或多个文件更改，重构代码</div>
    </div>
    <div>
      <h5>运行命令</h5>
      <div class="text-sm" style="color: #64748b;">获取终端命令建议</div>
    </div>
    <div>
      <h5>自动化工作流程</h5>
      <div class="text-sm" style="color: #64748b;">搜索、推理和执行来自动化工作流程，例如新建一个项目</div>
    </div>
  </div>
</div>

<!--
自动化工作流程

1. 搜索：自动扫描您的整个代码库，找到相关文件
2. 推理：分析代码结构、依赖关系、设计模式等
3. 执行：自动进行多步骤操作，比如：
  + 创建多个文件
  + 修改配置文件
  + 更新多个组件
  + 重构整个模块
-->

---

# AI对话模式有哪些

AI对话提供了针对特定任务优化的不同模式：

<AgentMode />

<!--
+ 询问模式:
 Ask 与其他默认模式（代理和手动）不同，因为它默认不应用任何建议的更改 - 这使它成为一种"只读"模式，具有读取文件和其他上下文的全部能力，但没有能力自行进行任何更改。
 不想更改的代码库或在实施之前使用 AI 规划解决方案非常有用！


+ 手动模式:
用于在您确切知道需要进行哪些更改以及在哪里进行更改时进行有针对性的代码修改
与代理模式不同，它不会探索代码库或运行终端命令；它完全依赖于您的具体指令和您提供的上下文（例如，通过@提及文件）。
当您需要控制力和精准度时，手动模式尤为出色，它就像一位 AI 结对程序员，执行您的特定计划。


+ 自定义模式:
允许您使用适合您工作流程的工具和提示来创建新模式。这些模式是对内置的"代理"、"询问"和"手动"模式的补充。

  + 学习：专注于彻底解释概念 工具：全部Search
  + 重构：只专注于改进现有代码结构，不添加新功能 工具：Edit & Reapply
  + 研究：从各种来源收集大量信息，包括网络搜索和代码库探索。 工具：Codebase，Web，Read file，Search files

 -->

---

# 代理模式详解/Agent

<AgentModeDetail></AgentModeDetail>

<!--

Agent 是 Cursor 中默认且最自主的模式，旨在以最少的指导处理复杂的编码任务。
它启用了所有工具，可以自主探索代码库、阅读文档、浏览网页、编辑文件以及运行终端命令，从而高效地完成任务。

 -->

---

# 核心功能--AI对话--内联编辑 (⌘K)

快速内联代码编辑和生成。

- 直接在编辑器窗口中生成新代码或编辑现有代码。

- 终端中使用通过提示栏界面生成并运行命令

<div data-name="frame" class="frame p-2 not-prose relative bg-gray-50/50 rounded-2xl overflow-hidden dark:bg-gray-800/25"><div class="absolute inset-0 bg-grid-neutral-200/20 [mask-image:linear-gradient(0deg,#fff,rgba(255,255,255,0.6))] dark:bg-grid-white/5 dark:[mask-image:linear-gradient(0deg,rgba(255,255,255,0.1),rgba(255,255,255,0.5))]" style="background-position: 10px 10px;"></div><div class="relative rounded-xl overflow-hidden flex justify-center"><span aria-owns="rmiz-modal-b648cf7870f8" data-rmiz=""><span data-rmiz-content="found" style="visibility: visible;"><img src="https://mintlify.s3.us-west-1.amazonaws.com/cursor/images/cmdk/regular.png"></span><span data-rmiz-ghost="" style="height: 365px; left: 0px; width: 655px; top: 0px;"><button aria-label="Expand image" data-rmiz-btn-zoom="" type="button"><svg aria-hidden="true" data-rmiz-btn-zoom-icon="true" fill="currentColor" focusable="false" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg"><path d="M 9 1 L 9 2 L 12.292969 2 L 2 12.292969 L 2 9 L 1 9 L 1 14 L 6 14 L 6 13 L 2.707031 13 L 13 2.707031 L 13 6 L 14 6 L 14 1 Z"></path></svg></button></span></span></div><div class="absolute inset-0 pointer-events-none border border-black/5 rounded-2xl dark:border-white/5"></div></div>

<!--
编辑器中有3种模式：
+ 内联编辑
+ 整个文件编辑
+ 快速提问


终端命令 K
+ 快速提问

 -->

---

# 4. Cursor怎么用得更个性化

<ul class="my-8">
<li class="my-2">代码库索引 🔍</li>
<li class="my-2">Rules - 智能上下文规则 📋</li>
<li class="my-2">@ 符号 - 智能上下文引用 🎯</li>
<li class="my-2">MCP - 模型上下文协议 🔌</li>
</ul>

---

# 代码库索引 🔍

让 AI 更深入理解您的整个代码库

<div class="grid grid-cols-2 gap-8 mt-8">
  <div class="space-y-6">
    <div class="bg-gradient-to-r from-blue-50 to-indigo-50 p-4 rounded-lg border border-blue-200 dark:from-blue-900/20 dark:to-indigo-900/20 dark:border-blue-700">
      <h3 class="text-lg font-semibold text-blue-800 dark:text-blue-300 mb-2">🎯 核心原理</h3>
      <p class="text-sm text-blue-700 dark:text-blue-400">为每个文件生成嵌入向量，大幅提升 AI 对代码的理解和搜索准确性</p>
    </div>
    <div class="bg-gradient-to-r from-blue-50 to-indigo-50 p-4 rounded-lg border border-blue-200 dark:from-blue-900/20 dark:to-indigo-900/20 dark:border-blue-700">
      <h3 class="text-lg font-semibold text-green-800 dark:text-green-300 mb-2">⚙️ 工作方式</h3>
      <ul class="text-sm text-green-700 dark:text-green-400 space-y-1">
        <li>打开项目时自动开始索引</li>
        <li>新文件自动添加到索引</li>
        <li>支持 <code>.gitignore</code> 和 <code>.cursorignore</code></li>
      </ul>
    </div>
  </div>

  <div class="space-y-6">
    <div class="bg-gradient-to-r from-orange-50 to-pink-50 p-4 rounded-lg border border-orange-200 dark:from-orange-900/20 dark:to-pink-900/20 dark:border-orange-700">
      <h3 class="text-lg font-semibold text-orange-800 dark:text-orange-300 mb-2">💡 最佳实践</h3>
      <ul class="text-sm text-orange-700 dark:text-orange-400 space-y-1">
        <li>使用 <code>.cursorignore</code> 选择性索引</li>
        <li>忽略不相关的大型文件</li>
        <li>多根工作区支持多项目开发</li>
      </ul>
    </div>

  </div>
</div>

<!--
代码库索引是 Cursor 的智能索引系统，通过为每个文件生成嵌入向量来提升 AI 的代码理解能力。

核心优势：
- 提供更准确的代码搜索结果
- 增强 AI 对整个项目的理解
- 支持大型项目和多项目工作区
- 智能文件过滤和忽略机制

配置选项：
- 自动索引新仓库
- 自定义忽略规则
- 多根工作区支持
- 针对大型单体仓库的优化策略
-->

---

# Rules - 智能上下文规则 📋

通过可重用的作用域指令控制 Agent 模型的行为

<div class="grid grid-cols-2 gap-8 mt-8">
<div>

## 🎯 什么是 Rules？

为项目或个人提供持久的上下文、偏好设置或工作流程编码方式

## ⚡ 核心原理

大型语言模型在补全过程中不会保留记忆。规则通过在提示级别提供持久且可重用的上下文来解决这个问题。

</div>
<div>

## 🔧 适用范围

- Chat/Agent 和 ⌘K 模式
- 代码生成和编辑
- 工作流程指导

## 📁 规则类型

- 项目规则 (Project Rules)
- 用户规则 (User Rules)
- 传统规则 (.cursorrules)

</div>
</div>

<!--
每一次会话都是一次新的会话，不会保留之前的上下文。

规则的意义是 告诉大模型一些一定需要的提示词。应用规则时，规则将包含在模型上下文的开头。

cursorrules（遗产）已弃用，但仍被兼容
 -->

---

# 项目规则 (Project Rules)

存储在 `.cursor/rules` 中，版本控制且范围限定于代码库

<div class="grid grid-cols-2 gap-8 mt-8">
<div class="grid gap-1 mt-1">

### 🎯 使用场景

- 编码特定领域知识到代码库中
- 自动化项目特定的工作流程或模板
- 标准化风格或架构决策

### 📝 规则类型

- **Always:** 总是包含
- **Auto Attached:** 文件匹配时自动包含
- **Agent Requested:** AI 决定是否包含
- **Manual:** 手动触发 @ruleName

</div>
<div>

### 📄 MDC 格式示例

```yaml
---
description: RPC Service boilerplate
globs: "**/*.service.ts"
alwaysApply: false
---

- 使用内部 RPC 模式定义服务
- 始终使用 snake_case 命名服务

@service-template.ts
```

### 🔄 创建方式

- ⌘ + Shift + P → "New Cursor Rule"
- Cursor Settings → Rules
- Chat 中生成规则

</div>
</div>

---

# @ 符号 - 智能上下文引用 🎯

在 Cursor 中使用 @ 符号引用代码、文件、文档和其他上下文

<div class="grid grid-cols-2 gap-8 mt-8">
<div>

## 🚀 基本使用

在 Agent、Ask 和 ⌘K 中输入 `@`，会弹出建议菜单，自动根据输入过滤最相关的建议

### ⌨️ 快捷操作

- **上/下箭头键** - 浏览建议列表
- **Enter** - 选择建议
- **自动过滤** - 根据输入显示相关项目

</div>
<div>

## 部分可用 @ 符号的列表

- @Files——引用项目中的特定文件

- @Folders - 引用整个文件夹以获得更广泛的上下文

- @Code - 引用代码库中的特定代码片段或符号

- @Docs——访问文档和指南

- @Git——访问 git 历史记录和更改

- @Web——引用外部网络资源和文档

</div>
</div>

---

# MCP - 模型上下文协议概述 🔌

连接外部工具和数据源到 Cursor 的强大插件系统

<div class="grid grid-cols-2 gap-8 mt-8">
<div>

### 🎯 什么是 MCP？

Model Context Protocol (MCP) 是一个**开放式标准协议**，它规范了应用程序向 LLM 提供上下文和工具的方式。MCP工具可以理解为 Cursor 的插件系统，它允许您通过标准化接口将 Agent 连接到各种数据源和工具，从而扩展 Agent 的功能。

</div>
<div>

### 🚀 核心优势

- **统一接口** - 一套标准连接所有工具和数据源
- **读写并举** - 既可查询数据也可执行操作命令
- **实时交互** - 动态获取最新信息和状态
- **多语言支持** - 支持Python、TypeScript、Java、C#等主流语言开发

</div>
</div>

<!--
不使用MCP的话：
通过提示词 给AI描述前情提要。这就像是你必须当"翻译官"，不断向 AI 解释项目的外部环境。

我的数据结构是什么？第三方服务的配置是什么？我使用了那些外部工具，等等

使用MCP后：

直接连接外部系统，
不再需要你描述数据库，AI 可以直接访问查看表结构，
不用解释 API，AI 能直接调用和测试接口

从 "手动描述" 转向 "自动发现"：

Before: 你是信息的搬运工

After: AI 是信息的主动获取者

MCP 让 Cursor 具备了"自我学习项目环境"的能力，而不是依赖你的描述。这样既提高了准确性，也大大减少了沟通成本。
 -->

---

# 🗺️ 高德地图 MCP 使用流程

<div class="grid grid-cols-2 gap-8 mt-8">

<div>

### 1. 配置文件

https://blog.csdn.net/Dontla/article/details/147577827

```json
{
  "mcpServers": {
    // 基于SSE（Server-Sent Events），服务器发送事件
    "amap-sse": {
      "url": "https://mcp.amap.com/sse?key=xxx"
    }
  }
}
```

</div>
<div>

### 2. 使用示例

- 地址解析和地理编码
- 路径规划和导航
- 周边搜索（餐厅、医院等）
- 实时交通信息查询

</div>
</div>

<!--
eg

我想从北京市丰台区东铁匠营街道宋庄路26号院骑行至北京市奥体中心，请帮我规划路线。

哇哦，骑行的时间好长啊。那我还是选择地铁吧，请帮我规划地铁路线。

我希望能用高德地图显示行程。你可以做到吗？

 -->

---

# MCP 工具集成和应用场景 🛠️

丰富的第三方集成，大幅扩展 Cursor 的能力边界

<div class="grid grid-cols-2 gap-8 mt-8">
<div>

## 🗄️ 数据库和存储

### 直接数据库访问

- **PostgreSQL/MySQL** - 无需手动提供 schema
- **SQLite** - 本地数据快速查询
- **Redis** - 缓存和会话管理
- 自动生成查询语句和数据分析

## 🌐 第三方服务

### 开发工具

- **GitHub** - PR 创建、代码搜索、问题管理
- **GitLab** - 项目管理和 CI/CD

</div>
<div>

## 🧠 AI 增强

### 智能功能

- **Memory** - 长期记忆和上下文保持
- **Web Search** - 实时信息检索

</div>
</div>

<!--


 -->

---

# 谢谢！

进一步探索 Cursor，提升您的编码体验。

[cursor.sh](https://cursor.sh/)
