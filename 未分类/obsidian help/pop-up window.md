### 第一部分：核心功能对照翻译与逻辑解析

#### 1. 功能概述 (Introduction)

**Original:** This feature is only available on Desktop. You can open separate pop-out windows in Obsidian. Each pop-out window is associated with its respective vault window. If you close a vault window, all of its pop-out windows will close as well.

**中文翻译：** 此功能仅适用于桌面端（Mac/Windows/Linux）。你可以在 Obsidian 中打开独立的窗口。每个独立窗口都与其对应的库（Vault）主窗口相关联。如果你关闭了主窗口，所有相关的独立窗口也会随之关闭。

- **逻辑解析：** 这里的逻辑是 **“主从架构”**。虽然窗口看起来是独立的，但它们共享同一个“大脑”（即你的 Obsidian 库设置和插件）。这确保了你在不同窗口编辑时，数据和配置是完全实时同步的。
    

#### 2. 在新窗口打开文件 (Open a file in a new window)

**Original:** File explorer: Right-click a note and select Open in new window. Command palette: Select Open current tab in new window. Tab: Right-click a tab and select Open in new window.

**中文翻译：** - **文件管理器：** 右键点击一篇笔记，选择“在新窗口中打开”。

- **命令面板：** 选择“在新窗口中打开当前标签页”。
    
- **标签页：** 右键点击标签页并选择“在新窗口中打开”。
    

- **逻辑解析：** 这体现了 **“多焦点协作”**。Obsidian 允许你打破单一主界面的限制。你可以右键点击任何笔记或链接将其“弹出”，这意味着你可以同时并排查看多个笔记，不受主窗口布局的限制。
    

#### 3. 跨窗口移动文件 (Move a file to a different window)

**Original:** You can drag the file to a tab group in the destination window. In the Command palette, select Move current tab in new window. Right-click a tab and select Move to new window.

**中文翻译：** - 你可以将文件拖动到目标窗口的标签组中。

- 在命令面板中，选择“将当前标签页移至新窗口”。
    
- 右键点击标签页并选择“移至新窗口”。
    

- **逻辑解析：** 这进一步强化了我们上一篇提到的 **“拖放逻辑”**。窗口之间不再有边界，文件可以在不同窗口之间自由“流动”。这让你的整个桌面都变成了你的工作空间，而不仅仅是 Obsidian 软件内部。
    

---


- **Obsidian 逻辑深度理解：**
独立窗口功能证明了 Obsidian 的 **“非线性”** 本质。它不希望你被困在一个层级分明的文件夹结构里，而是希望你根据当下的需要，自由地在桌面上排布你的知识碎片。
