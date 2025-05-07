# Color-颜色

好看的颜色主题

# 常用配色

gruvbox

solarized

dracula

catppuccin

### 配色

dracula

gruvbox

solarized

nord

castelle

one dark

monokai

material

catppuccin

tomorrow

Flexoki

## miku配色方案

背景色：背景的颜色，没有设计的配色一般是白色或黑色

前景色：一般是最常见的字体的颜色，一般与背景色相反，为黑色或白色

配色中红、绿、蓝、黄色：一般配色都有这四个颜色或不到四个的相似颜色

注释-警告-错误色：代码注释颜色，警告部分颜色，错误部分颜色

焦点色：把某一段选取即置于焦点，此时应该改变背景或前景为焦点色

一般配色方案只需要以下的颜色，从里面可重复的选一些进行搭配：红，绿，黄，蓝，紫，青，黑，白，灰

---

不做两方案设计，只设计单方案，目前为亮方案

背景：39c5bb faafbe?

前景：282828?

红色：d80000 蓝色：0000ff 绿： 黄：

注释：ffe211警告：ffa500错误：红色

焦点：33ffcc

# Styling Guidelines

[https://github.com/chriskempson/base16/blob/main/styling.md#styling-guidelines](https://github.com/chriskempson/base16/blob/main/styling.md#styling-guidelines)

颜色 base00 到 base07 通常是一种色调的变化，从最深到最浅。这些颜色用于前景和背景、状态栏、行高亮等。颜色 base08 到 base0F 通常是用于类型、运算符、名称和变量的单独颜色。为了创建一个深色主题，颜色 base00 到 base07 应该从深到浅。对于一个浅色主题，这些颜色应该从浅到深。

[https://github.com/chriskempson/base16/blob/main/styling.md#styling-guidelines](https://github.com/chriskempson/base16/blob/main/styling.md#styling-guidelines)

**Version 0.2 版本 0.2**

Base16 aims to group similar language constructs with a single colour. For example, floats, ints, and doubles would belong to the same colour group. The colours for the default theme were chosen to be easily separable, but scheme designers should pick whichever colours they desire, e.g. base0B (green by default) could be replaced with red. There are, however, some general guidelines below that stipulate which base0B should be used to highlight each construct when designing templates for editors.Base16 旨在将相似的语言结构归为一组，使用单一颜色表示。例如，浮点数、整数和双精度数应属于同一颜色组。默认主题的颜色选择易于区分，但方案设计者可以根据喜好选择任意颜色，例如 base0B（默认为绿色）可替换为红色。不过，在设计编辑器模板时，以下有一些通用指南规定了每种结构应使用哪个 base0B 进行高亮显示。

Since describing syntax highlighting can be tricky, please see [base16-vim](https://github.com/chriskempson/base16-vim/) and [base16-textmate](https://github.com/chriskempson/base16-textmate/) for reference. Though it should be noted that each editor will have some discrepancies due the fact that editors generally have different syntax highlighting engines.由于描述语法高亮可能较为复杂，请参考 base16-vim 和 base16-textmate 作为示例。但需注意，由于各编辑器的语法高亮引擎不同，每个编辑器可能会有一些差异。

Colours base00 to base07 are typically variations of a shade and run from darkest to lightest. These colours are used for foreground and background, status bars, line highlighting and such. colours base08 to base0F are typically individual colours used for types, operators, names and variables. In order to create a dark theme, colours base00 to base07 should span from dark to light. For a light theme, these colours should span from light to dark.颜色 base00 到 base07 通常是同一色调的不同深浅，从最深到最浅排列。这些颜色用于前景、背景、状态栏、行高亮等。颜色 base08 到 base0F 通常是独立的颜色，用于类型、运算符、名称和变量。要创建深色主题，base00 到 base07 应从深到浅排列；对于浅色主题，则应从浅到深排列。

- **base00** - 默认背景

- **base01** - 较亮背景（用于状态栏、行号和折叠标记）

- **base02** - 选择背景

- **base03** - 注释、不可见字符、行高亮

- **base04** - 深色前景（用于状态栏）

- **base05** - 默认前景、插入符、分隔符、运算符

- **base06** - 浅色前景（不常用）

- **base07** - 浅色背景（不常用）

- **base08** - 变量、XML 标签、标记链接文本、标记列表、差异删除

- **base09** - 整数、布尔值、常量、XML 属性、标记链接 URL

- **base0A** - 类、标记加粗、搜索文本背景

- **base0B** - 字符串、继承类、标记代码、差异插入

- **base0C** - 支持、正则表达式、转义字符、标记引号

- **base0D** - 函数、方法、属性 ID、标题

- **base0E** - 关键字、存储、选择器、标记斜体、差异更改

- **base0F** - 已弃用、打开/关闭嵌入式语言标签，例如 `<?php?>`

- **base00** - Default Backgroundbase00 - 默认背景

- **base01** - Lighter Background (Used for status bars, line number and folding marks)base01 - 较浅背景（用于状态栏、行号和折叠标记）

- **base02** - Selection Backgroundbase02 - 选中背景

- **base03** - Comments, Invisibles, Line Highlightingbase03 - 注释、不可见字符、行高亮

- **base04** - Dark Foreground (Used for status bars)base04 - 深色前景（用于状态栏）

- **base05** - Default Foreground, Caret, Delimiters, Operatorsbase05 - 默认前景色、插入符、分隔符、运算符

- **base06** - Light Foreground (Not often used)base06 - 浅色前景（不常用）

- **base07** - Light Background (Not often used)base07 - 浅色背景（不常用）

- **base08** - Variables, XML Tags, Markup Link Text, Markup Lists, Diff Deletedbase08 - 变量、XML 标签、标记链接文本、标记列表、差异删除部分

- **base09** - Integers, Boolean, Constants, XML Attributes, Markup Link Urlbase09 - 整数、布尔值、常量、XML 属性、标记链接 URL

- **base0A** - Classes, Markup Bold, Search Text Backgroundbase0A - 类、标记加粗、搜索文本背景

- **base0B** - Strings, Inherited Class, Markup Code, Diff Insertedbase0B - 字符串、继承类、标记代码、差异插入部分

- **base0C** - Support, Regular Expressions, Escape Characters, Markup Quotesbase0C - 支持、正则表达式、转义字符、标记引用

- **base0D** - Functions, Methods, Attribute IDs, Headingsbase0D - 函数、方法、属性 ID、标题

- **base0E** - Keywords, Storage, Selector, Markup Italic, Diff Changedbase0E - 关键字、存储、选择器、标记斜体、差异更改部分

- **base0F** - Deprecated, Opening/Closing Embedded Language Tags, e.g. `<?php ?>`base0F - 已弃用，用于打开/关闭嵌入式语言标签，例如 `<?php ?>`

### **1. 色彩空间的感知差异挑战**

- **核心问题**：人类对颜色的亮度感知存在差异（如黄色比蓝色更显明亮），而传统数字色彩模型（如RGB）无法完全反映这种差异。

- **解决思路**：使用基于人类视觉感知的**色彩空间**（如CIELAB、Oklab）来协调颜色，确保设计在不同亮度下保持视觉一致性。

---

### **2. CIELAB色彩空间**

- 由国际照明委员会（CIE）于1976年提出，基于人眼对颜色的感知均匀性设计。

- **优势**：直观反映人眼对亮度、色相的感知差异，适合设计协调的配色方案。

- Ethan Schoonover在设计Solarized（2011年）时，利用CIELAB的亮度关系（L*值）确保颜色在不同背景下（如代码编辑器）的对比度和可读性。

---

### **3. Oklab色彩空间**

- 2021年提出的新型色彩空间，旨在改进CIELAB的均匀性缺陷。

- 通过更精确的数学模型模拟人眼感知，尤其在**明暗极端区域（如深色或高亮）**保持色彩关系的一致性。

---

### **5. 色彩强度指数增强的意义**

- **实现方式**：Oklab通过非线性（指数）调整色彩通道的强度，使颜色在低浓度时饱和度衰减更平缓，避免传统模型（如RGB）直接降低饱和度导致的灰暗感。

---



