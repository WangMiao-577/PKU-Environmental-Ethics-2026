# 环境伦理学

2026–2027 学年个人学习归档 · Simson。

当前资料为课堂笔记及其 PDF，涵盖环境伦理学的发展、环境现状和环境问题。按已有内容整理，后续资料可继续放入相应分类。

GitHub 公开仓库：[PKU-Environmental-Ethics-2026](https://github.com/WangMiao-577/PKU-Environmental-Ethics-2026)。每个课程目录有自己的独立 Git 历史。

## 从哪里开始

- [课堂笔记源码](Notes/Environment%20Ethic.tex)
- [课堂笔记 PDF](Notes/Environment%20Ethic.pdf)
- [资料索引](FILE_INDEX.md)

## 目录

- `Notes/`：课堂笔记、主 LaTeX 文件、章节源码、插图与已有 PDF。

## 本地编译

与三个主目录的布局配套时，在本课程根目录运行：

```bash
python3 "../../latex/build.py" "Notes/Environment Ethic.tex"
```

编译脚本会切换到主文件所在目录，使用工作区已有 MiKTeX/XeLaTeX，并关闭缺包自动安装。源码引用的章节和图片均保持在对应 Notes 目录内。单独获取此课程仓库时，可用自己已有的 XeLaTeX 在 Notes 中编译；中文与代码字体使用本机已有字体。

## 保存范围与来源

课程资料和已有学习结果完整保留。LaTeX 中间产物、依赖缓存与生成构建文件只在本地保存，不进入公开仓库。第三方材料保留原文件名、README、LICENSE 或版权说明；这些资料的权利属于原作者，本仓库不为它们追加统一开放许可证。内容仍以现有课堂记录为准，整理没有补写尚未完成的章节。
