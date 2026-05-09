### 第一部分：核心功能对照翻译与逻辑解析

#### 1. 概述 (Introduction)

**Original:** There are many ways to drag and drop elements in Obsidian. This includes tabs, files, folders, and content.

**中文翻译：** 在 Obsidian 中，有多种方式可以进行拖放操作。这包括标签页（Tabs）、文件、文件夹以及具体的笔记内容。

- **逻辑解析：** 拖放不仅仅是“移动位置”，它是 Obsidian **“空间化管理”** 的体现。Obsidian 认为笔记不是死板的列表，而应该是可以被随意拆解、重组的模块。
    

#### 2. 拖动标签页 (Drag tabs)

**Original:** You can arrange tabs and split tab groups in the main content area and in sidebars.

**中文翻译：** 你可以在主内容区和侧边栏中排列标签页，或者拆分布局（创建标签组）。

- **逻辑解析：** 这对应了 **“多维工作流”** 逻辑。你可以把参考资料拖到左边，写作区放在中间，大纲放在右边。拖放操作让你能根据当下的任务（比如一边看韩语单词，一边记录用法）快速构建最适合的屏幕布局。
    

#### 3. 拖动来源 (Drag sources)

**Original:** You can drag a file, or multiple files from the file explorer. You can drag a file from a search result. You can drag a file from backlinks or unlinked references. You can drag a file from a link inside the note, in preview mode.

**中文翻译：** 你可以从文件浏览器中拖动单个或多个文件。你也可以从搜索结果、反向链接（Backlinks）或未链接引用中拖动文件。甚至在预览模式下，你可以直接拖动笔记内部的链接。

- **逻辑解析：** 这体现了 **“全局一致性”**。在 Obsidian 里，只要你看到一个文件名，它就是一个可以被操作的对象。无论它是在搜索结果里，还是在反向链接里，你都能直接“拎”起来用，打破了功能模块之间的界限。
    

#### 4. 放置目标 (Drop destinations)

**Original:** You can drop a file on a tab header to open the file there. You can drop a file on a folder in the file explorer to move the file there. You can drop a file into an editor to insert it as a link.

**中文翻译：** 你可以将文件拖到标签页头部以在该处打开文件。你可以将文件拖到文件夹上以移动它。你可以将文件拖入编辑器，将其插入为一个链接（Internal Link）。

- **逻辑解析：** 这是 **“自动化链接”** 逻辑。当你把一个笔记拖进另一个笔记时，软件会自动帮你写好 `[[文件名]]`。这鼓励你通过物理动作去建立笔记间的联系，而不是手动输入。
    

#### 5. 从外部拖入 (Dragging from outside Obsidian)

**Original:** You can drag any HTML content from the browser into Obsidian to automatically convert them into Markdown. You can drag and drop any files from your native file explorer to have Obsidian import those files in your vault's attachment folder and insert them as internal links.

**中文翻译：** 你可以将浏览器里的任何 HTML 内容拖入 Obsidian，它会自动转换为 Markdown 格式。你可以将电脑本地的文件拖入 Obsidian，软件会将其复制到你的“附件文件夹”中，并在当前笔记里插入内部链接。

- **逻辑解析：** 这体现了 **“本地优先与数据集成”**。Obsidian 作为一个“外挂硬盘”，需要方便地吸收外界信息。它通过拖放自动转换格式，确保你收集的所有资料最终都以纯文本（Markdown）或本地附件的形式存在你的电脑里。
    

---


这个功能的逻辑其实就是一句话：**“看见即所得，拖动即连接”**。
