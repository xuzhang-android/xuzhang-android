<div align="center">

# 👋 你好，我是 xuzhang

### @xuzhang-android &nbsp;·&nbsp; Android 系统 &nbsp;·&nbsp; Linux 内核 &nbsp;·&nbsp; 底层工具链

[![GitHub followers](https://img.shields.io/github/followers/xuzhang-android?label=Followers&style=social)](https://github.com/xuzhang-android)
[![GitHub stars](https://img.shields.io/github/stars/xuzhang-android?affiliations=OWNER&label=Total%20Stars&style=social)](https://github.com/xuzhang-android)

</div>

---

## 🙋 关于我

- 📱 **Android 系统维护与开发**：解锁与 root、隐藏环境、系统属性与挂载命名空间、Zygisk / LSPosed 模块、SELinux 策略
- 🐧 **Linux 系统与内核**：GKI 内核构建与定制、init / boot 流程、容器与命名空间、交叉编译、崩溃与 panic 现场排查
- 🧰 **工具链与工程化**：命令行工具、桌面客户端、CI 流水线、打包与签名、跨平台分发
- 🧠 **AI 基础设施**：模型网关、鉴权与配额、渠道调度
- ⚙️ 常用 Kotlin · Java · C / C++ · Rust · Go · Python · TypeScript · Dart · Shell
- 🌏 中文母语

---

## 🔭 当前方向

- **Android 系统层**：GKI 内核构建与排障、开机流程（init / boot / preinit）、系统属性与挂载、root 与隐藏环境
- **Linux 系统维护**：内核裁剪与编译、systemd 与容器、交叉编译工具链、性能与稳定性排查
- **底层工具开发**：命令行与桌面工具、模块化 hook 生成、脚本与自动化
- **工程化**：多平台 CI、制品构建与签名、版本与发布流程
- **其他软件**：AI 模型网关、Web 前端、内部效率工具

---

## 🤝 参与贡献

### 🧱 [ABK · AnyBase Kernel](https://github.com/xingguangcuican6666/ABK)

> **C · Python · Flutter · GitHub Actions**
>
> GKI 内核构建工具链（AnyBase Kernel）。提交 5 项修复：复用工作流的输入名错误、CLI 的 XDG 配置目录解析与旧配置迁移提示、桌面端 LTS 组合不可达、fork PR 上 macOS arm64 矩阵腿拿不到 runner、manifest 重写吞掉注释。

---

### 🧩 [KernelSU](https://github.com/tiann/KernelSU)

> **C · Rust · Python · 构建与打包**
>
> Android root 方案（GKI / LKM 双模式）。提交 4 项修复：通知脚本读取 `head_commit` 的键名错误、注入 `libksud.so` 不跟随 APK 打包方式、build-tools 预发布版本排在正式版之前、repack 失败会先删掉上一次的成品。

---

### 🧩 [meow-api](https://github.com/xingguangcuican6666/meow-api)

> **Go · React**
>
> AI 模型网关（new-api 下游）。提交 3 项修复：前端查询缓存键冲突、渠道调度的冷却与熔断绕过、OAuth refresh token 归属校验顺序。

---

### 🛠 [DeviceToolbox](https://github.com/xuzhang-android/DeviceToolbox)

> **Kotlin · C++ · Zygisk**
>
> 自研 Android 机型伪装工具箱：系统级属性改写 + Zygisk 逐应用伪装。

---

### 🧪 [NyaSU](https://github.com/xuzhang-android/NyaSU) ／ [KernelSU](https://github.com/xuzhang-android/KernelSU) fork

> **C · Kotlin · Rust · Python**
>
> 在 KernelSU 生态上做实验：函数级 hook 生成器（构建期产出可 `git apply` 的补丁）、模块化内核改动合并。

---

## 🚀 Tech Stack

<div align="center">

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🧭 能帮上忙的地方

| 场景 | 具体内容 |
|:--|:--|
| Android 系统 | 解锁与 root 流程、隐藏环境、系统属性 / 挂载、模块编写与调试、开机阶段问题定位 |
| 内核 | GKI 内核配置与编译、补丁与符号问题、启动失败与 panic 日志分析 |
| 构建与发布 | 多平台 CI、制品打包与签名、缓存与增量构建、发布流程自动化 |
| 工具开发 | CLI / 桌面端工具、脚本自动化、内部效率软件 |
| AI 基础设施 | 模型网关部署与鉴权、渠道与配额、前后端联调 |

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=xuzhang-android&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&rank_icon=github)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=xuzhang-android&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

</div>

---

## 👀 Visitors

<div align="center">

![Visitor](https://count.getloli.com/@xuzhang-android?name=xuzhang-android&theme=asoul&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto)

</div>

---

<div align="center">

*"保持好奇，持续折腾。"*

<sub>Stay curious. Keep tinkering.</sub>

</div>
