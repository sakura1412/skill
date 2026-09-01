# 标注（Biaozhu）Codex 插件

“标注”会结合当前任务中的需求信息与项目页面实现，为每个页面的按钮、输入框、选择器、标签页及其他交互控件添加可编辑的编号气泡。点击气泡后，详细说明会集中显示在页面右侧。

## 安装

在终端中添加此插件市场：

```bash
codex plugin marketplace add sakura1412/skill
```

重启 Codex 或 ChatGPT 桌面应用，在 Plugins Directory 中选择 **Sakura1412 Skills**，然后安装 **标注**。

也可以只安装独立 Skill：

```text
使用 $skill-installer 从以下地址安装：
https://github.com/sakura1412/skill/tree/main/plugins/biaozhu/skills/biaozhu
```

## 使用

在项目任务中输入：

```text
使用 $biaozhu，根据当前任务历史和页面实现，为所有页面添加可编辑的编号气泡标注。
```

Skill 会要求实际检查所有可访问页面和标签页，确保标注不阻止原页面操作，并且切换标签后只显示当前标签对应的标注。

## 注意

- Skill 只能使用当前任务中可见的对话上下文和项目资料，不能自动读取其他独立任务的聊天记录。
- 若目标系统只有访问链接而没有源码，永久嵌入标注通常需要用户脚本、浏览器扩展或目标系统的部署权限。
- 不要将客户密码、访问令牌或其他敏感数据写入 Skill。
