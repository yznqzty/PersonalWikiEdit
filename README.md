# 萌娘百科编辑存档

该仓库为个人编辑存档内容，以及部分百页面源代码缓存。

Archive 中的内容为缓存，遵循原来的著作权许可，其他全为个人书写，除已经提交到萌娘百科的按照萌娘百科的 [知识共享 署名-非商业性使用-相同方式共享 3.0 中国大陆（CC BY-NC-SA 3.0 CN）许可协议](https://creativecommons.org/licenses/by-nc-sa/3.0/cn)，遵循 MIT 著作权许可。

不应在此处[提交 Issue](https://github.com/yznqzty/PersonalWikiEdit/issues) ，除非你要反馈[视频](https://github.com/yznqzty/PersonalWikiEdit/blob/main/Video.md)问题（虽然说我大概率不会处理），建议在[百科](https://mzh.moegirl.com.cn)上直接修改页面。

该 wiki 标记语言可能与[维基百科](https://wikipedia.org)不兼容。

随仓库附[联系方式](Contact.md)、[侵权删除](Del.md)、[存档视频](Video.md)和 [MIT Licence（含原文和翻译）](LICENCE)。

## 主题色

图片的主题色为开源软件 Aves 图片信息最底下的 10 个颜色。标记使用 `$0` ~ `$9` 如果有歧义则使用 `C$0` ~ `C$9` 。

## 特殊标记

特殊标记适用于模版和 AI 提示词。

- `// 注释`：注释，没有提交到百科中，在编辑时应该被执行/注意；
- `%内容%`：固定含义，见下表；
- `$内容$`：替换变量。

## 文本文件特殊后缀

- `.ext`：标签以及个人记录信息，使用 2 个 `\n` 来分隔是之前记录的还是编辑时记录的；
- `.info`：文件对应的提交信息；
- `.infomodel`：文件对应的提交信息的模版；
- `.prompt`：给 AI 的提示词，`$` 可以替换为文件或代入的内容；
- `.promptmodel`：AI 提示词的模版；
- `.wiki`：Wiki 标记语言；
- `.wikiext`：有标签和个人记录信息前缀的 Wiki 标记语言，标签和正文使用 2 个 `\n` 来分隔；
- `.wikimodel`：Wiki 标记语言模版。