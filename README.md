<div align="center">

# 📚 EasyTranslater

### 🚀 Zotero 全文翻译插件

**让文献阅读更简单，让语言不再成为科研阅读的障碍。**

<p>
  <img src="https://img.shields.io/badge/Zotero-Plugin-blue?style=flat-square&logo=zotero" alt="Zotero Plugin">
  <img src="https://img.shields.io/badge/PDF-Full%20Translation-orange?style=flat-square" alt="PDF Translation">
  <img src="https://img.shields.io/github/license/haoge678/EasyTranslater?style=flat-square" alt="License">
  <img src="https://img.shields.io/github/stars/haoge678/EasyTranslater?style=flat-square" alt="Stars">
</p>

<p>
  <a href="#-功能特点">功能特点</a> ·
  <a href="#-全文翻译">全文翻译</a> ·
  <a href="#-使用方法">使用方法</a> ·
  <a href="#-安装">安装</a> ·
  <a href="#-常见问题">常见问题</a>
</p>

</div>

---

## ✨ EasyTranslater 是什么？

**EasyTranslater** 是一款面向 Zotero 用户的全文翻译插件。

它可以直接对 Zotero 中的 PDF 文献进行全文翻译，将原始 PDF 中的文字内容转换为目标语言，并尽可能保留原文的**页面结构、段落布局、公式、图片以及整体排版**。

无需反复复制粘贴文本，也无需离开 Zotero 使用其他翻译工具。

> **打开文献 → 一键翻译 → 直接阅读**

---

## 🎯 为什么选择 EasyTranslater？

科研阅读中，经常会遇到这样的情况：

* 📄 PDF 文献篇幅很长，逐段复制翻译效率低
* 🌐 英文文献阅读困难，需要频繁切换翻译工具
* 📐 PDF 中存在公式、图片、表格等复杂内容
* 📝 普通文本翻译无法很好地还原 PDF 原始布局
* 🔄 翻译完成后还需要重新整理和排版

**EasyTranslater 希望解决的，就是这些问题。**

它不是简单的“复制文字 → 翻译”，而是围绕 **PDF 全文翻译** 这一场景进行设计。

---

# 🚀 核心功能

<div align="center">

|        功能        | 说明                 |
| :--------------: | :----------------- |
|  📖 **PDF 全文翻译** | 一次处理整篇 PDF 文献      |
|   🎨 **保留原文排版**  | 尽可能保持原 PDF 页面结构    |
|    🧮 **公式保留**   | 尽可能保留论文中的数学公式      |
|   🖼️ **图片保留**   | 翻译过程中保留原文图片内容      |
|   📑 **段落结构保持**  | 尽可能维持原始段落与页面布局     |
|    ⚡ **批量处理**    | 减少重复的复制、粘贴操作       |
| 🔌 **Zotero 集成** | 直接围绕 Zotero 文献进行处理 |
|   🌍 **多语言翻译**   | 根据所使用的翻译服务支持不同语言   |

</div>

---

# 📖 全文翻译

## 一键处理 PDF 文献

EasyTranslater 的核心功能是 **PDF 全文翻译**。

选择 Zotero 中需要处理的 PDF，即可对整篇文献进行翻译。

<div align="center">

<img src="docs/images/full-translation.png" width="90%" alt="EasyTranslater PDF 全文翻译">

</div>

---

## 🎨 尽可能保留原文格式

不同于只提取文字进行翻译的工具，EasyTranslater 会对 PDF 内容进行处理，并尝试恢复翻译后的页面结构。

例如：

* 标题层级
* 段落结构
* 双栏布局
* 图片
* 表格
* 数学公式
* 页眉页脚
* 页面位置

<div align="center">

<img src="docs/images/compare.png" width="90%" alt="原文与翻译结果对比">

</div>

> **目标不是单纯得到一份译文，而是得到一份可以继续阅读的翻译版 PDF。**

---

# 🧠 翻译流程

EasyTranslater 的全文翻译并不是简单地将 PDF 文字直接发送给翻译服务。

大致流程如下：

```text
┌──────────────┐
│  Zotero PDF  │
└──────┬───────┘
       ↓
┌──────────────┐
│  PDF 内容解析 │
└──────┬───────┘
       ↓
┌──────────────┐
│ 文本 / 公式 / │
│ 图片 / 布局分析│
└──────┬───────┘
       ↓
┌──────────────┐
│   翻译处理    │
└──────┬───────┘
       ↓
┌──────────────┐
│ PDF 页面重建  │
└──────┬───────┘
       ↓
┌──────────────┐
│   翻译版 PDF  │
└──────────────┘
```

因此，**PDF 全文翻译的处理时间通常会明显高于普通文本翻译**。

这是因为除了翻译本身，还涉及 PDF 解析、内容处理、公式处理以及页面重新生成等步骤。

---

# 🛠️ 使用方法

## 1. 在 Zotero 中选择 PDF

首先在 Zotero 中找到需要翻译的 PDF 文献。

<div align="center">

<img src="docs/images/step-1.png" width="85%" alt="选择 PDF">

</div>

---

## 2. 启动 EasyTranslater

通过 EasyTranslater 提供的功能入口启动全文翻译。

<div align="center">

<img src="docs/images/step-2.png" width="85%" alt="启动全文翻译">

</div>

---

## 3. 选择翻译配置

根据实际需求选择相应的翻译服务及目标语言。

<div align="center">

<img src="docs/images/step-3.png" width="85%" alt="翻译配置">

</div>

---

## 4. 等待翻译完成

PDF 全文翻译涉及多个处理步骤。

对于篇幅较长、排版复杂或包含大量公式和图片的论文，处理时间可能会更长。

<div align="center">

<img src="docs/images/step-4.png" width="85%" alt="翻译处理中">

</div>

---

## 5. 阅读翻译后的 PDF

翻译完成后即可查看生成的翻译版 PDF。

<div align="center">

<img src="docs/images/result.png" width="90%" alt="翻译结果">

</div>

---

# 📦 安装

> 以下内容可根据项目实际发布方式进行调整。

## 方式一：安装插件

下载最新版本的 EasyTranslater 插件文件，并按照 Zotero 插件安装方式进行安装。

```text
Zotero
  ↓
工具
  ↓
附加组件
  ↓
设置
  ↓
从文件安装插件
  ↓
选择 EasyTranslater 插件文件
```

安装完成后重启 Zotero。

---

## 方式二：从源码运行

```bash
git clone https://github.com/haoge678/EasyTranslater.git

cd EasyTranslater
```

然后按照项目源码中的环境要求进行配置。

---

# 🌍 翻译服务

EasyTranslater 本身主要负责：

**PDF 解析 → 内容处理 → 翻译调用 → PDF 重建**

实际翻译效果和速度会受到所使用的翻译服务、模型、网络环境以及 PDF 本身复杂程度影响。

不同翻译服务之间可能存在：

* 翻译质量差异
* 翻译速度差异
* 上下文理解能力差异
* 专业术语处理差异
* 使用额度或费用差异

因此：

> **EasyTranslater 不对第三方翻译服务的最终翻译质量作绝对保证。**

对于论文发表、医学、法律、专利等专业场景，建议将机器翻译结果作为**辅助阅读工具**，重要内容仍应结合原文进行核对。

---

# 📊 适合哪些人？

EasyTranslater 更适合以下用户：

### 🎓 学生

阅读英文论文、毕业论文、课程资料。

### 🔬 科研人员

快速浏览英文研究论文，降低语言阅读成本。

### 📚 文献阅读者

面对大量英文 PDF 时，提高初步阅读效率。

### 💻 Zotero 用户

希望直接在 Zotero 工作流中完成 PDF 翻译，而不是频繁切换软件。

---

# 💡 使用建议

### 长文献建议分批处理

对于几十页甚至上百页的论文，建议根据实际情况进行处理。

### 复杂 PDF 可能需要更长时间

扫描版 PDF、复杂双栏排版、大量公式、复杂表格等内容都会增加处理难度。

### 翻译结果建议作为辅助

机器翻译并不能完全替代人工翻译。

尤其是：

* 专业术语
* 数学推导
* 实验方法
* 法律条款
* 医学内容
* 论文结论

建议结合原文进行确认。

---

# ❓ 常见问题

<details>
<summary><b>为什么 PDF 全文翻译需要较长时间？</b></summary>

PDF 全文翻译不是单纯的文本翻译。

在翻译过程中，还需要进行 PDF 解析、文本提取、公式及图片处理、页面布局恢复以及最终 PDF 生成，因此处理时间通常会比普通文本翻译更长。

</details>

<details>
<summary><b>为什么翻译后的排版和原文不可能 100% 一致？</b></summary>

PDF 本身属于固定页面格式，而不同语言的文字长度、字体以及字符宽度都可能存在差异。

因此，在翻译后重新生成 PDF 时，很难保证每一个字符都与原文保持完全相同的位置。

EasyTranslater 的目标是**尽可能保持原文结构和视觉布局**。

</details>

<details>
<summary><b>公式会不会被翻译？</b></summary>

EasyTranslater 会尽可能识别并保留论文中的数学公式。

实际效果取决于 PDF 本身的结构以及公式复杂程度。

</details>

<details>
<summary><b>扫描版 PDF 可以翻译吗？</b></summary>

扫描版 PDF 通常需要先进行 OCR 才能获得可翻译的文本。

具体支持情况取决于当前版本以及 PDF 本身的内容结构。

</details>

<details>
<summary><b>翻译速度为什么比较慢？</b></summary>

全文翻译需要经过 PDF 解析、内容处理、翻译以及 PDF 重建等多个步骤。

因此：

**PDF 越复杂、页数越多 → 通常处理时间越长。**

这属于全文 PDF 翻译本身的处理特点。

</details>

---

# 🗺️ Roadmap

* [ ] 更完善的 PDF 排版恢复
* [ ] 更好的公式处理
* [ ] 更好的表格处理
* [ ] 更多翻译服务支持
* [ ] 更完善的错误处理
* [ ] 批量文献翻译
* [ ] 更多 Zotero 工作流支持

---

# 🤝 贡献

欢迎提交：

* 🐛 Bug
* 💡 Feature Request
* 🔧 Pull Request
* 📖 使用建议

如果你在使用过程中遇到问题，也欢迎通过 GitHub Issues 反馈。

---

# ⭐ 支持项目

如果 EasyTranslater 对你的论文阅读、文献翻译有所帮助：

<div align="center">

### ⭐ 给项目点一个 Star

你的 Star 是对项目持续维护最大的鼓励 ❤️

</div>

---

# 📄 License

本项目遵循项目仓库中声明的 License。

使用 EasyTranslater 时，请遵守相关第三方翻译服务的使用条款以及当地法律法规。

---

<div align="center">

## EasyTranslater

**Make academic reading easier.**

Made with ❤️ for Zotero users.

</div>
