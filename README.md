# Financial - Android 收支管理系统

## 一、项目简介

Financial 是一个基于 Android 平台的本地收支管理应用，主要用于记录和管理个人的日常收入、支出及便签信息。  
本项目采用 **SQLite 本地数据库**，无需联网，适合作为 Android 课程设计 / 实训项目。

应用支持收入与支出的新增、修改、删除、统计分析以及数据导出等功能，界面简洁，操作直观。

---

## 二、功能介绍

### 1. 用户功能
- 用户登录
- 修改登录密码

### 2. 收入管理
- 新增收入记录
- 查看收入列表
- 修改收入信息
- 删除收入记录

### 3. 支出管理
- 新增支出记录
- 查看支出列表
- 修改支出信息
- 删除支出记录

### 4. 统计分析
- 本月收入 / 支出统计
- 本周收入 / 支出统计
- 本月结余自动计算

### 5. 数据导出
- 将收入或支出记录导出为 TXT 文件
- 文件保存至设备 Downloads/financial 目录

### 6. 便签功能
- 新增便签
- 查看便签列表
- 用于记录临时事项或备注信息

---

## 三、技术栈

| 技术 | 说明 |
|----|----|
| 开发语言 | Java |
| 开发环境 | Android Studio |
| Android API | API 28 |
| 数据库 | SQLite |
| UI | XML 布局 |
| 架构 | Activity + Adapter + SQLite |

---

## 四、运行环境

- Android Studio 3.x 及以上
- Android SDK 28
- 模拟器或真机（Android 8.0 及以上推荐）

---

## 五、项目结构说明

```text
com.example.financial
├── activity        // 各功能 Activity
├── adapter         // ListView / CursorAdapter
├── db              // SQLiteOpenHelper
├── util            // 工具类（如导出功能）
└── entity          // 实体类（可选）

