# Week 1

## **Week1 主题：双系统安装 + 开发环境搭建 + Git 基础学习**

### **一、课程目标（Learning Objectives）**

通过本周学习，学生应能够：

1. 完成 Windows 11 + Ubuntu 20.04 的双系统安装与启动切换。
2. 学会 VSCode 的编程使用，安装 C++环境。
3. 学会使用 Git 进行基本的代码管理操作（init / add / commit / push）。
4. 学习使用 Markdown 编写实验报告。
5. 在 GitHub 上完成个人仓库创建，并成功提交第 1 周作业。

---

## **二、本周教学内容（Teaching Content）**

### **1. 双系统安装（Win11 + Ubuntu20.04）**

- BIOS 设置（UEFI、Secure Boot、启动顺序）
- Windows 分区压缩与 Ubuntu 镜像写盘
- 手动分区（EFI / SWAP / EXT4 Root）
- GRUB 配置与启动菜单
- 常见故障解决（黑屏、无法进入 Windows、引导修复）

### **2.VSCode 安装与使用**

- Ubuntu 下安装 VSCode
- 安装必要的扩展
- 开发与调试基础

### **3. Ubuntu 基础配置**

- 换源（中科大、清华）
- 安装常用工具：`git`、`vim`、`curl`、`build-essential`

### **4. Git 基础操作**

核心命令：

```bash
git init
git config --global user.name "yourname"
git config --global user.email "your@email.com"

git add .
git commit -m "week1 submit"

git branch -M main
git remote add origin https://github.com/xxx/xxx.git
git push -u origin main
```

### **5. Markdown 报告规范**

学生必须掌握：

- 标题 `#`
- 粗体 `**...**`
- 代码块 `code`
- 插入图片
- 列表、有序列表

---

## **三、本周实训任务（Practical Tasks）**

### **任务 1：安装双系统（必做）**

- Ubuntu 安装完成截图
- Windows + Ubuntu 双系统启动菜单截图
- Ubuntu 桌面截图

### **任务 2：VSCode 的安装与配置（必做）**

- C++ 插件安装
- 在 VSCode 中运行 C++ 的 Hello World

### **任务 3：完成 Git 学习与作业上传（必做）**

- 加入自己的 Github 小组（例如 Group 1 的 Github 仓库网址为：
  https://classroom.github.com/classrooms/246406408-2025biuhcourse-classroom-group1 ，其他小组只需修改网址最后的数字即可）
- 创建自己的 Github 账号（用户名格式：姓名\_学号）
- 完成 Git 命令的学习
- 将作业使用命令提交到 Github 对应的仓库中。

### **任务 4：编写 Markdown 实验报告（必做）**

实验报告要求：

| 内容项          | 要求                             |
| --------------- | -------------------------------- |
| 实现全过程说明  | 需清晰描述步骤与方法             |
| 实验截图 / 视频 | 必须提供运行结果                 |
| 问题记录        | 包含原因分析与尝试过程           |
| 模块理解        | 对知识点进行总结                 |
| 文件命名规范    | `team_张三_week1_draft.md(周五)` |
|                 | `team_张三_week1_final.md(周天)` |

## **四、提交方式（Submission）**

请将本周所有内容上传至你的 GitHub 仓库：
- 每个组有不同的链接
- 每一次的作业链接会提前发布在群里

在提交时需要提交.md 文件以及内容材料（如实验截图、视频等，保存在创建的新文件夹中）。

## **五、参考材料**

### **1. Ubuntu 系统安装**

-[Ubuntu20.04 双系统安装详解](https://blog.csdn.net/wyr1849089774/article/details/133387874)

### **2. VSCode 的安装与配置**

-[Ubuntu 环境下安装 VSCode](https://blog.csdn.net/LL596214569/article/details/106445990)

### **3. Git 入门**

-[Github 入门教程](https://blog.csdn.net/black_sneak/article/details/139600633)\
-[Github 加速](https://blog.csdn.net/B11050729/article/details/132131659)

### **4. Markdown 文件**

-[Markdown 教程](https://zhuanlan.zhihu.com/p/598132171)
