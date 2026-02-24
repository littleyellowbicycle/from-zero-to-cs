# 🌱 From Zero to CS  
> **一个非科班程序员的计算机基础补习日志**

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

你是否也和我一样——  
没有计算机学位，却想真正理解代码背后的机器？  
刷过 LeetCode，却对“为什么这段代码慢”感到迷茫？  
听说过缓存、流水线、虚拟内存，但总觉得它们像黑盒？

**这个仓库，就是我的答案。**

在这里，我从零开始，系统补全计算机科学（Computer Science）的核心基础。不为速成，只为**真正理解**：  
> **程序是如何在 CPU 上跑起来的？操作系统到底做了什么？网络请求背后经历了哪些旅程？**

---

## 📚 学习路线（持续更新）

本仓库按“自底向上”原则组织，覆盖现代软件工程师必备的底层知识：

| 模块 | 内容 | 状态 |
|------|------|------|
| **1. 计算机组成原理** | CPU 指令执行、缓存体系、内存层次、汇编初探 | ✍️ 编写中 |
| **2. 操作系统** | 进程/线程、虚拟内存、文件系统、系统调用 | ⏳ 待启动 |
| **3. 网络基础** | TCP/IP、HTTP、DNS、Socket 编程 | ⏳ 待启动 |
| **4. 编译与链接** | 预处理 → 编译 → 汇编 → 链接全过程 | ⏳ 待启动 |
| **5. 实战项目** | 手写简易 shell、内存分配器、HTTP 服务器 | ⏳ 规划中 |

> 💡 所有内容均以 **Markdown 笔记 + 可运行代码示例 + 性能实验** 形式呈现，拒绝“纸上谈兵”。

---

## 🔍 当前重点：CPU 与缓存

最近我深入研究了 **CPU 如何执行指令** 和 **缓存优化**，已完成以下笔记：

- [`cpu/how-cpu-executes-an-instruction.md`](cpu/how-cpu-executes-an-instruction.md)  
  从图灵机到现代流水线，揭秘 `a = 1 + 2` 的 CPU 之旅。
  
- [`cpu/cpu-cache-deep-dive.md`](cpu/cpu-cache-deep-dive.md)  
  缓存结构、映射方式、替换策略，以及**如何写出缓存命中率更高的代码**。

- [`tools/perf-and-cachegrind-guide.md`](tools/perf-and-cachegrind-guide.md)  
  使用 `perf` 和 `cachegrind` **实测缓存性能**，让优化有据可依。

每一篇都包含：
- ✅ 清晰的技术解释  
- ✅ 可复现的 C/C++ 示例  
- ✅ 配图描述（便于后续可视化）  
- ✅ 面向程序员的“钩子”与实战建议

---

## 🛠️ 为什么值得参考？

- **非科班视角**：跳过数学证明，聚焦**工程师真正需要的理解**；
- **问题驱动**：从“LeetCode 跑得慢”“多线程性能差”等真实痛点出发；
- **可验证**：所有结论均可通过 `perf`、`gdb`、`strace` 等工具验证；
- **开源共建**：欢迎 Issue 讨论、PR 补充，一起把地基打牢！

---

## 🙌 致谢与参考

- 《深入理解计算机系统》（CSAPP）—— 我的精神导师
- [Computer Science Crash Course (YouTube)](https://www.youtube.com/playlist?list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo)
- Intel® 64 and IA-32 Architectures Software Developer Manuals
- Linux `perf` / Valgrind 官方文档
- xiaolincoder https://github.com/xiaolincoder/CS-Base --超级大牛
- 知乎一众大牛
---

## 📜 License

本仓库内容采用 [MIT License](LICENSE)，欢迎学习、分享、二次创作。

---

> **“我们不是在学计算机科学，我们是在重建对计算机的信任。”**  
> —— 一个正在路上的非科班程序员

🌟 如果你觉得这些笔记有帮助，不妨点个 **Star**，让我知道我不是一个人在战斗！
