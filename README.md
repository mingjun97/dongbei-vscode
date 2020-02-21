# dongbei-vscode

东北话编程vscode语法高亮插件

东北话编程主仓库： https://github.com/zhanyong-wan/dongbei

## 特性

亮就完事了。

## 已知问题

- [ ] 部分关键字高亮不够美型(如`在` `整`)
- [ ] syntax awareness识别（例如识别`算九九乘法咋整：`中函数名为`算九九乘法`，而非高亮数值关键字`九九`）

## 测试方法

git clone最新版repo（确保`.vscode/launch.json`文件存在）后直接F5（或在debug面板中点击启动）启动插件。

测试syntax识别结果可参照[这里](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide)，激活如下快捷键指令后即可使用该指令查看识别scope。
```json
{
  "key": "cmd+alt+shift+i",
  "command": "editor.action.inspectTMScopes"
}
```

Any contribution helps a lot!


## 版本日志

### 0.0.2

增加`没毛病` `有毛病` `抱团`

### 0.0.1

能用辣！
