<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Tableaunoir

[![集成程度](https://apps.yunohost.org/badge/integration/tableaunoir)](https://ci-apps.yunohost.org/ci/apps/tableaunoir/)
![工作状态](https://apps.yunohost.org/badge/state/tableaunoir)
![维护状态](https://apps.yunohost.org/badge/maintained/tableaunoir)

[![使用 YunoHost 安装 Tableaunoir](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tableaunoir)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Tableaunoir。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Tableaunoir is an online collaborative blackboard tool with fridge magnets available in many languages. "Tableau noir" means blackboard in French. Contrary to plenty of other collaborative boards on the Internet, with Tableaunoir you can create interactive animations via the use of fridge magnets.

### Features

- Of course, you can draw and erase, with your mouse or a graphic tablet. You can draw shapes.
- Collaborate edit the same board at the same time (need a server for that), does not require an account
- Backgrounds: staffs for teaching music, grid, images and PDF documents
- You can also use kind of predefined fridge magnets that you can move on the board, to make animation e.g. for illustrating sorting algorithms, graphs algorithms etc (and even playing Go!).
- Create your own fridge magnets for interactive courses, by importing any image, or by transforming a part of the board (Ctrl + X).
- Color palette for chalk (c, 7 colors black/white #000000, yellow #FFFF00, orange #FFA500, blue #64ACFF, red #DC143C, pink #DDA0DD, green #32CD32),
- Draw interative graphs : vertices are magnets, labels of vertices and edges are handwritten but are updated when vertices are moved,
- Change the color of magnets' background,
- Load/Save the current board,
- Export in PNG or PDF,
- Add texts (Enter and type), and move texts. Supports LaTeX (using MathJax)!
- Switch to a whiteboard instead of a blackboard, or any background color
- Change from right-handed (default) to left-handed cursor,
- Divide yourboard in half. Ideal for teaching. Add as many new half-board as you need, going right with → and then left/right with ←/→ keyboard arrows,
- Make slides, record animations. This can be used to prepare slides for a talk or for a video.


**分发版本：** 0.1~ynh2

**演示：** <https://tableaunoir.github.io/>

## 截图

![Tableaunoir 的截图](./doc/screenshots/screenshot.jpg)

## 文档与资源

- 官方应用网站： <https://tableaunoir.github.io/>
- 上游应用代码库： <https://github.com/tableaunoir/tableaunoir>
- YunoHost 商店： <https://apps.yunohost.org/app/tableaunoir>
- 报告 bug： <https://github.com/YunoHost-Apps/tableaunoir_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/tableaunoir_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tableaunoir_ynh/tree/testing --debug
或
sudo yunohost app upgrade tableaunoir -u https://github.com/YunoHost-Apps/tableaunoir_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
