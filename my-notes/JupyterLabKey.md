以下是 MacOS 下 Jupyter lab 最常用的快捷键。快捷键在两种模式下执行，进入编辑模式用 `⏎`，回到命令模式用 `⎋`（ESC）。

另外，代码编辑过程中需要安装 Jupyterlab 插件 [@ryantam626/jupyterlab_sublime](https://github.com/ryantam626/jupyterlab_sublime) 之后才能使用 “多行同时编辑功能”。


| 快捷键                                  | 说明                                                         | 模式   |
| --------------------------------------- | ------------------------------------------------------------ | ------ |
| `ESC`                                   | 从编辑模式回到命令模式                                       | 命令   |
| `A`                                     | 在当前 Cell 之前插入一个 Cell                                |        |
| `B`                                     | 在当前 Cell 之后插入一个 Cell                                |        |
| `D`, `D`                                   | 连续按两次 `d` 键，删除当前 Cell                                                |        |
| `Y`                                     | 将当前 Cell 设置为 Code Cell                                 |        |
| `M`                                     | 将当前 Cell 设置为 Markdown Cell                             |        |
| `^ ⇧ - `                                | 将当前 Cell 拆分为两个                                       | 编辑    |
| `⇧ M`                                   | 合并选中的 Cells                                             |        |
| `⇧ J` or `⇧ ↓`                          | 连续向下选中 Cells                                           |        |
| `⇧ K` or `⇧ ↑`                          | 连续向上选中 Cells                                           |        |
| `⇧ ⏎` or `^ ⏎`                          | 运行当前 Cell 中的代码                                       |        |
| `⇧ L`                                   | 显示/隐藏代码行号                                            |        |
| `⏎`                                     | 当前 Cell 进入编辑模式                                       | 编辑   |
| `⇥`                                   | 自动补全代码                               |        |
| `⇧ ⇥`                                   | 呼出当前光标下词汇的 Docstring                               |        |
| `⌘ D`                                   | Sublime Keymap: 选中下一个相同字符串                         |        |
| `⇧ ⌘ L`                                 | Sublime Keymap: 在选中的行内启动多行同时编辑                 |        |
| `⌘ + Mouse Click`                       | 生成下一个可同时编辑的光标点                                 |        |