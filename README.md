# 小牛同学的毕业论文

基于 [WHU-Thesis](https://github.com/whutug/whu-thesis) 修改，感谢 `WHU-Thesis` 团队！

<br>

## 关于本人

`LaTex` 初学者，只会对葫芦画瓢.

<br>

## 使用说明

> *老周，开发环境已经配好了，这部分可以跳过啦.*

请配合 [`Visual Studio Code`](https://code.visualstudio.com/)  + `LaTex Workshop` + [`Tex Live 2020`](https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/Images/texlive2020.iso) 使用.

如出现生成失败等问题，请确保 `Tex Live` 的相关宏包已经更新至最新.

```powershell
# 使用以下命令更新宏包
tlmgr update --self --all
```

<br>

## 目录与文件说明

- `.vscode` 包含本项目所需的 `LaTex Workshop` 的配置文件，其中关闭了**自动生成**，指定所有的输出文件输出至 `build` 文件夹下，指定PDF使用内置浏览器浏览.

- `build` 包含 `main.pdf` 以及生成之所需的辅助文件.

- `data` 包含必要的 GBT 规范文件，以及武汉大学的校名PDF.

- `demo` 包含 `WHU-Thesis` 项目提供的示例文件及其PDF，如有需要请复制到根目录生成.

- `doc` 包含 `WHU-Thesis` 项目的使用指南.

- `figures` 包含论文中使用的插图文件.

- `pages` 包含论文各部分的 `tex` 文件，会在 `main.tex` 中被引用.

- `ref` 包含 `bibtex` 格式的引用.

- `main.tex` 为主文件，请使用该文件生成PDF.

- `whu-thesis.cls` 提供必需的样式和格式规定.

<br>

## 相关链接

- [武汉大学毕业论文（设计）智能管理系统](http://210.42.121.231/bysj/)

- [关于认真做好2020届本科生 毕业论文（设计）答辩工作的通知](https://info.whu.edu.cn/info/2268/5690.htm)

- [关于开展2021届本科生毕业论文(设计) 选题工作的通知](https://info.whu.edu.cn/info/2268/5606.htm)

<br>

<details>
<summary></summary>
<br>
我是懒狗.

不想写毕设.

就比如我花了半个小时写这个 `readme` 也不想看论文.

</details>