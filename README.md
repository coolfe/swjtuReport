# SWJTU 课程论文模板
📌 **原作者**：Pungjay  
- GitHub: [Pungjay/swjtuReport](https://github.com/Pungjay/swjtuReport)  
- Overleaf: [Overleaf 项目链接](https://www.overleaf.com/)

📌 **原原作者**：jweihe  
- GitHub: [jweihe/UCAS_Latex_Template](https://github.com/jweihe/UCAS_Latex_Template)  
- Overleaf: [中国科学院大学课程论文模板](https://www.overleaf.com/latex/templates/zhong-guo-ke-xue-yuan-da-xue-ke-cheng-lun-wen-mo-ban/nphpxhhqvnds)

📌 **二编作者**：coolfe  


---
📅 **最后更改于**：2024/11/11
## ✨ 11.11模板优化内容

1. **字体强制设置**：解决了之前生僻字无法显示的问题，虽然具体原因尚不明确，但报错已经消除，暂不深究。
2. **段落格式调整**：设置段落首行缩进，行距为固定值 20 磅。由于笔者是新手，一开始没有使用 `\paragraph` 关键字，总之通过添加两行设置实现了效果。
3. **图表字号设置**：图表名设置为小五号，创建了一个新的字号并应用。
4. **定理格式修改**：由于自定义的定理格式无法使用 `autoref`，进行了修改，现在改为使用 `cref`。
5. **引用样式调整**：引用按顺序标注为 1、2、3，使用关键词 `unsrt`（原来的 `plain` 是按作者名字排序）。同时，文献引用显示在角标位置，因此做了一些相关设置。
6. **文本框样式调整**：根据个人喜好，修改了文本框样式，添加了灰色边框，使其更加美观。
7. **代码样式设置**：为了插入 Python 代码，专门设置了代码样式。
