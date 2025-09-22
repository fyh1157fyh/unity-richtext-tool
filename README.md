# Unity RichText Generator

一个基于浏览器的 **Unity 富文本生成器**，支持 **UGUI** 与 **TextMesh Pro (TMP)**。  
帮助美术和策划快速生成 `<b> <i> <color> <size> <u> <s> <mark> <link>` 等标签，避免手写出错。

## 在线使用
👉 [GitHub Pages 地址](https://<你的用户名>.github.io/unity-richtext-tool/)

在飞书云文档里可以直接插入“网页”块，粘贴上面的地址，全员可用。

## 功能特性
- **UGUI 模式**：支持 `<b> <i> <color> <size>`  
- **TMP 模式**：支持 `<u> <s> <mark> <link>` 以及 `<sprite>`  
- **所见即所得**：输入框里直接写，选中后点击按钮自动插标签  
- **一键复制**：复制结果直接粘到 Unity Inspector  
- **清除标签**：选中文本或整段，一键移除所有 `<…>`  

## 使用方法
1. 进入在线地址或打开本地 `index.html`。  
2. 输入文本，选中部分后点击工具栏按钮（加粗/斜体/颜色/字号/下划线等）。  
3. 右侧“生成结果”区会实时显示拼好的富文本字符串。  
4. 点击“复制结果”，粘贴到 Unity UGUI Text 或 TextMeshPro 组件。  

## 截图示例
<img width="1223" height="553" alt="image" src="https://github.com/user-attachments/assets/bd6d2f77-f53c-4e65-8b70-ade640c46224" />


## 本地运行
无需任何依赖，直接保存 `index.html`，用浏览器打开即可。  
推荐 Chrome / Edge / Firefox / Safari 等现代浏览器。

## 许可
MIT License  
可自由使用、修改、分发本项目代码。
