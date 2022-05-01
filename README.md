# TJUThesis_master_2021
天大博士/硕士学位论文Latex模板，根据2021年版要求修改，可直接在Overleaf上运行。

# 主要贡献
- 参考[tjuthesis_master_2016](https://github.com/jiangqideng/tjuthesis_master_2016)和[TJUThesisLatexTemplate](https://github.com/twtstudio/TJUThesisLatexTemplate), 依照《天津大学关于博士、硕士学位论文统一格式的规定（2021年修订）》中要求进行格式修改。
- 此外，鉴于[tjuthesis_master_2016](https://github.com/jiangqideng/tjuthesis_master_2016)只能先由latex编译成dvi在转换成pdf的形式较为繁琐，现已修改为由xelatex直接编译并生成pdf。因此，本模板可直接在Overleaf或TeXstudio中同时编辑和预览。

:star:使用该模板所写的论文已通过盲审、查重和答辩，成功提交天津大学图书馆存档！（2021.12.24）

# 更新2022.5.1
1. 感谢[HikariTJU](https://github.com/HikariTJU)同学提醒，独创性声明中“天津大学”的字体已修正。
   - 请大家确保自己的Windows中安装了楷体_GB2312字体，否则word默认为宋体。然后你就会像我一样打开《格式规定》后看到独创性声明中“天津大学”是宋体。
   - 但是图书馆并不注意这件事，我当时能顺利提交，可能是因为他们也清楚，并不是每个电脑都有楷体_GB2312。
2. 提高了对模板对生僻字繁体字的支持。
   - **详细做法请在**`setup/format.tex`**中搜索**`备用解决方案`

# 使用方式
## Overleaf(推荐方式)
[Overleaf](https://www.overleaf.com/)是一个免费且不需要实名认证的在线Latex编辑平台，并且不需要翻墙。写过行文论文的同学应该知道，对于多人协作便捷以及管理已有tex文件相当方便。**相当于打开一个网页，在线编辑，远端服务器编译**，免去了Texlive安装的麻烦和电脑硬件设施的困扰。

[Overleaf和Latex快速上手视频教程](https://www.bilibili.com/video/BV1fA411W7kZ?from=search&seid=1945788916371918236&spm_id_from=333.337.0.0)

**建议在每次编辑后，把源码下载到本地保存！**

1. 注册账户并登录
2. 网页左上角点击“New Project”，选“Upload Project”，上传本模板的压缩包
3. 修改编译器：进入项目后，网页左上角点击“Menu”，在“Complier”中选择“XeLaTeX”
4. 开始编辑：
    1. 正文每章内容在body文件夹下*.tex文件中修改。若添加新章节，新建一个tex文件，并在编辑结束后在tjumain.tex的“正文部分内容”位置添加改tex文件
    2. 封面和摘要信息在preface文件夹下cover.tex中修改
    3. 附录、致谢、发表论文情况在appendix文件夹下对应tex文件修改
    4. 格式定义在setup文件夹下format.tex

## TeXLive+TeXstudio
本地编辑。亲测Win10+TeXLive2021+TeXstudio可行。
1. 安装TeXLive2021和TeXstudio
2. 修改默认编译器为XeLaTeX，“构建并查看”tjumain.tex
3. 参照上文修改内容

# 格式改动
以对比《天津大学关于博士、硕士学位论文统一格式的规定（2021年修订）》和《天津大学关于博士、硕士学位论文统一格式的规定(试行版) 》（2016年版）中的要求进行

1. 封面页修改格式，添加评审表格，添加“一级学科”。
2. 独创性声明，“天津大学”改为楷体_GB2312。
3. 中文摘要，中文关键词与内容摘要间隔一行，无缩进左对齐书写。“关键词：”采用宋体四号字加粗。
4. 英文摘要，英文关键词与内容摘要间隔一行。
5. 页眉：奇数页为相应的章标题或无编号章标题；偶数页为“天津大学硕士学位论文”。

注：**本模板样式要求为学硕。** 根据2021年版规定，博士（专业型和学术型）、专硕的要求区别于学硕如下：
1. 博士的页眉为“天津大学博士学位论文”
2. 博士的封面项目，如“一级学科”等，需要改变
3. 专硕的封面项目，如“企业导师”等，需要改变

# 免责声明
使用本模板带来的一切不利影响和损失，本人均不负责。

# 致谢

前辈们做出了不可磨灭的艰辛探索：

- [tjuthesis](https://code.google.com/archive/p/tjuthesis/)
- [TJUThesisLatexTemplate](https://github.com/twtstudio/TJUThesisLatexTemplate)
- [tjuthesis_master_2016](https://github.com/jiangqideng/tjuthesis_master_2016)

# 后记
- 希望大家能指正本模板的错误，特别是格式错误，为小王能顺利提交论文排雷解难。
- 感谢杨同学在小王研究本模板时的零食供应。
- 如果本模板对你有帮助，请给一个宝贵的Star。
