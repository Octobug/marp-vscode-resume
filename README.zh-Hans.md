# marp-vscode-resume

[`English`](README.md) | `简体中文`

- [marp-vscode-resume](#marp-vscode-resume)
  - [效果展示](#效果展示)
  - [依赖](#依赖)
  - [如何使用](#如何使用)
    - [自定义 CSS](#自定义-css)
  - [许可](#许可)

使用 marp-vscode 制作的 Markdown 简历模板。

这个模板被刻意做成古早风格。

> It's a feature, not a bug.

## 效果展示

使用[著名演员梁朝伟先生的公开资料](https://zh.wikipedia.org/wiki/%E6%A2%81%E6%9C%9D%E5%81%89)制作的在线示例：

- [octobug.github.io/marp-vscode-resume](https://octobug.github.io/marp-vscode-resume)

## 依赖

- [VS Code](https://code.visualstudio.com/)
- VS Code 插件
  - [marp-vscode](https://github.com/marp-team/marp-vscode)
  - [vscode-markdownlint](https://github.com/DavidAnson/vscode-markdownlint.git) (可选)

## 如何使用

![编辑环境](assets/editting.zh-Hans.jpg)

1. 克隆本仓库：

    ```sh
    git clone git@github.com:Octobug/marp-vscode-resume.git
    ```

2. 使用 VS Code 打开项目：

    ```sh
    code marp-vscode-resume
    ```

3. 使用 Markdown 语法编辑简历模板：[`templates/zh-Hans.md`](templates/zh-Hans.md)
4. 使用 marp-vscode 导出需要的格式：
    - 快捷键：`command/ctrl + shift + p`
    - 选择：`Marp: Export Slide Deck...`

    marp-vscode 最好的地方在于，它导出的文件和预览效果完全一致，支持的格式有：[HTML, PDF, PPTX, PNG, JPEG](https://github.com/marp-team/marp-vscode#export-slide-deck-to-html-pdf-pptx-and-image-%EF%B8%8F)

### 自定义 CSS

这是一个基于 [Marp gaia 主题](https://github.com/marp-team/marp-core/tree/main/themes#gaia) 修改的模板，而不是一个开箱即用的工具，因此你很可能需要根据自己的偏好修改细节。

- 主题样式文件为 [`theme/resume.css`](theme/resume.css)
- 关于自定义 Marp 主题，请参考：[Use custom theme CSS 🛡️](https://github.com/marp-team/marp-vscode#use-custom-theme-css-%EF%B8%8F)
- 如果想进一步基于 gaia 自定义样式，请参考其原始样式文件：[marp-core/themes/gaia.scss](https://github.com/marp-team/marp-core/blob/main/themes/gaia.scss)

## 许可

[Unlicense license](https://github.com/Octobug/marp-vscode-resume/blob/main/LICENSE).

欢迎任何人按照自己喜欢的方式基于此模板进行修改。
