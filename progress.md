# 学习进度追踪

| Day | 日期 | 内容 | 完成 | 用时(min) | 状态 | 最有成就感的1分钟 |
|-----|------|------|------|-----------|------|-------------------|
| 1   | 5.27 | 环境搭建 | [x] | 75 | 🟢 | 屏幕出现Hello,嵌入式! |
| 2   | 5.28 | VS Code+PATH | [x] | 60 | 🟢 | 中文不乱码了 |
| 3   | 5.29 | Git基础 | [x] | 90 | 🟢 | 第一次commit |
| 4   | 5.30 | GitHub | [x] | 75 | 🟢 | 代码在云端了 |
| 5   | 5.31 | SOP建立 | [x] | 40 | 🟢 | 工具链验证全部通过 |

---

## Day5验证问答（2026-06-01）

### 1. gcc --version 和 code --version 分别输出什么？
- **gcc** → `GCC 16.1.0 (MinGW-W64 x86_64-ucrt-posix-seh, built by Brecht Sanders, r1)`
- **code** → `VS Code 1.122.1 (x64)`

### 2. 你的GitHub仓库地址是什么？
- `https://github.com/Wzole/embedded-learning-journey`

### 3. 用一句话解释：git commit做了什么？
- 把暂存区的文件拍一张永久快照，保存到本地仓库的历史记录里。

### 4. 用一句话解释：git push做了什么？
- 把本地仓库的新commit推送到GitHub远程仓库，让云端也同步更新。

### 5. 每日学习SOP有几步？分别是什么？
- **6步**：① 打开VS Code + 终端 → ② `cd D:\embedded_learning` 进入目录 → ③ 学习当天内容 + 写代码 + 编译运行 → ④ `git add` 暂存改动 → ⑤ `git commit -m "简述"` 提交 → ⑥ `git push` 推到GitHub

### 6. 如果明天想编译一个hello.c，依次打开什么、输入什么命令？
- 打开 **VS Code** → 打开终端(Ctrl+`) → `cd D:\embedded_learning\projects` → 写代码保存为 `hello.c` → `gcc hello.c -o hello` → `./hello`

### 7. 如果代码编译报错，第一步排查动作是什么？
- **读错误信息的第一行**：看文件名、行号和错误描述，直接跳到那一行检查语法。

---

✅ **7/7 全部通过 → 进入第一阶段：C语言 + 电路基础**
