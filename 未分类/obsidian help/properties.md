更多设定阅读[obsidian官方操作手册](https://help.obsidian.md/properties)
### 第一部分：核心功能对照翻译与逻辑解析

#### 1. 什么是属性 (What are properties)

**Original:** Properties allow you to organize information about a note. Properties contain structured data such as text, links, dates, checkboxes, and numbers.

**中文翻译：** 属性允许你组织关于笔记的信息。属性包含结构化数据，如文本、链接、日期、复选框和数字。

- **逻辑解析：** **“元数据 (Metadata)”逻辑**。笔记内容是给你（人）看的，而属性主要是给 Obsidian（机器）看的。有了属性，你以后就可以轻松搜出“所有日期在 2 月且状态为‘已完成’的货运计划”。
    

#### 2. 添加属性 (Add properties to a note)

**Original:** There are several ways to add a property to a note: Use the `Cmd/Ctrl + ;` hotkey, or type `---` at the very beginning of a file.

**中文翻译：** 有几种方法可以给笔记添加属性：使用快捷键 `Cmd/Ctrl + ;`，或者在文件的最开头输入三个横杠 `---`。

- **逻辑解析：** **“文档首部 (Frontmatter)”**。属性必须放在笔记的最顶端。一旦你输入 `---`，Obsidian 就会自动弹出一个美观的表格界面让你填写。
    

#### 3. 属性类型 (Property types)

**Original:** Obsidian supports the following property types: Text, List, Number, Checkbox, Date, Tags.

**中文翻译：** Obsidian 支持以下属性类型：文本、列表、数字、复选框、日期、标签。

- **逻辑解析：** **“数据格式化”**。如果你选了“日期”类型，Obsidian 会弹出一个日历让你选；如果你选了“复选框”，它会显示一个勾选框。这能保证你输入的数据是整齐统一的。
    

#### 4. 默认属性 (Default properties)

**Original:** Obsidian provides several default properties: `tags`, `cssclasses`, and `aliases`.

**中文翻译：** Obsidian 提供了几个默认属性：`tags`（标签）、`cssclasses`（样式类）和 `aliases`（别名）。

- **逻辑解析：** **“系统级关联”**。比如你在属性里填了 `tags`，它会自动关联到你右侧边栏的标签视图里。
    

---

### 第二部分：对小双的实际应用建议

这一功能对你的工作和学习有着巨大的提升作用：

- **管理货运计划（数据库化）：**
    
    你可以在每篇计划笔记顶部添加以下属性：
    
    - `日期`: 2026-02-11 (Date 类型)
        
    - `码头`: 蛇口港 (Text 类型)
        
    - `已完成`: [ ] (Checkbox 类型)
        
    - **逻辑：** 这样你不需要翻找笔记内容，看一眼顶部的属性表就能知道这篇笔记的核心背景。
        
- **韩语单词卡片（结构化）：**
    
    在每个单词笔记顶部设置：
    
    - `词性`: 名词 (Text 类型)
        
    - `掌握程度`: 3 (Number 类型，1-5 分)
        
    - `关联课次`: 第五课 (Text 类型)
        
    - **逻辑：** 配合社区插件（如 Dataview），你可以一键生成一张表格，列出所有“掌握程度小于 3”的单词进行复习。
        
- **别名功能 (Aliases)：**
    
    如果你记了一个单词 `사과`，你可以在属性的 `aliases` 填入 `苹果`。
    
    - **逻辑：** 以后你在其他笔记里输入 `[[苹果]]`，Obsidian 也会聪明地链接到 `사과` 这篇笔记。
        

---

### 💡 小双的 Mac 专属提醒：

既然你使用的是 Mac，请记住添加属性的快捷键是 **`Command (⌘)` + `;`**。

