## 本库的what和why

- what？
	- 真实袒露的[[第二大脑]]
		- 均是个人每日灵感、阅读和写作的完整真实发布
	- 未经美化的[[数字花园]]
		- 笔记内容才是核心，为了正式发布而修葺枝桠有时反而丢失细节，而且费时费力
- why？
	- 用[[双链笔记]]做笔记，就像编程。源码可以开源，我的笔记又有何不可？各种博客都是博主发他想给你看的，那不是完整的他，只是局部的他。
	- 除了个人隐私，我的全部思考和想法，或短暂或永恒，或黑暗或光明，都可以公之于众，也许没有人看，但这是我的态度。
	- 其实这个事儿，有一位编程界的大佬已经做了，吾仰望之：[Andyʼs working notes](https://notes.andymatuschak.org/About_these_notes)

## 快速开始

1. 访问本库的实时在线版本，随意漫游，感受[[双链笔记]]和[[《卡片笔记写作法》|卡片笔记]]的魅力：[oldwinter的数字闺房](https://oldwinter.github.io/knowledge-garden/)。
2. 若简单漫游后，还算感兴趣，则`git clone`本库，并用[[obsidian]]、[[logseq]]或[[vscode]][^1]任意一款app打开本库后进行编辑和探索。
3. 确定先只使用obsidian，结合[[《卡片笔记写作法》]]的方法论，建立自己的[[个人知识管理|PKM(personal knowledge management)]]体系，打造自己的[[第二大脑]]。
4. obsidian是[[平台+插件]]理念加持下的操作系统级的笔记软件，可以看看本库使用的[[obsidian插件]]，并评估自己的需求进行增删，让插件更好地为自己服务。
5. 工具和方法论都熟悉了以后，不妨开始尝试结合[[logseq]]和[[vscode]]，共同完成一些obsidian实现起来不便的操作。

## 本库涉及app及作用

- [[obsidian]]
	- markdown传统文本型笔记，进行阅读和写作
		- 即[[永久笔记]]
	- 当前项目的文件夹式与标签式的管理
		- 即[[项目笔记]]
	- 多端同步
		- 借用第三方[[remotely save]]插件由[[onedrive]]负责云存储和同步
- [[logseq]]
	- 大纲型笔记，进行日志和随笔记录
		- 即[[闪念笔记]]
	- 发布至[[github]]
		- 使用[[gtihub action]]自动定时发布，且action还有很大想象空间
- [[vscode]]
	- 文本和文件的批量编辑
	- 管理dot隐藏文件等非md文件的编辑
	- 借用copilot插件自动写作偶有奇效

## 周边app的联动与配合

- 本库聚焦于[[个人知识管理|PKM]]，而完整的工作和生活的效率体系，在我看来，共有4项
	- [[个人信息管理系统]]
		- 以[[devonthink]]为中心
	- [[个人任务管理系统]]
		- 以[[滴答清单]]为中心
	- [[个人知识笔记系统]] - 本库
		- 以[[obsidian]]为中心
	- [[个人输出发布系统]]
		- 以[[notion]]为中心
- 各个系统之间的联动与配合，参见[[效率系统4大子系统联动与配合]]

[^1]: vscode需额外安装foam插件后，便支持[[双链笔记]]的`[[`语法