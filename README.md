# 标题  
使用\#\可以来使文字变成标题（但是需要空一格）  
  一共可以设置6层标题  
  # 一级标题
  ## 二级标题
  ### 三级标题
  #### 四级标题
  ##### 五级标题
  ###### 六级标题

使用\**文字**\可以将文字加粗
适应\*文字*\可以倾斜文字*斜体文本*
使用\~文字~\~~删除\文本~~

使用\\\可以让这些符号（语法）不起作用

插入图片和链接  
[这是一个图片]![image](https://github.com/user-attachments/assets/6857d9ff-6a74-4d62-897c-f8e7ab51ff70)    
这里的[]是名称()是地址  
 地址直接复制网址或者粘贴图片即可  

[这是一个链接](https://www.example.com)  （这里不是网址而是在文件介绍中的路径）
  
无序列表：  
- 项目一
- 项目二
  - 子项目二点一
  - 子项目二点二

有序列表：
1. 第一项
2. 第二项
   1. 子项二点一
   2. 子项二点二


内联代码和代码块
\`这是内联代码`

\```python
\# 这是一个代码块
\def hello_world():
    print("Hello, World!")


  
\### 引用

\使用 `>` 来创建引用

\```markdown
\> 这是一个引用块。
\> 可以包含多个段落。

创建表格
\| 标题一 | 标题二 |
\| ------ | ------ |
\| 内容一 | 内容二 |
\| 内容三 | 内容四 |


创建任务列表（通常用于Issues和Pull Requests）
\- [x] 完成的任务
\- [ ] 未完成的任务


使用 --- 或 *** 创建分隔线
\---
\***

**实例**
\# 项目标题

\## 简介

\这是一个项目的简要介绍。

\### 特点

\- **简单**：易于使用。
\- **灵活**：可以根据需要进行定制。

\### 安装

\请按照以下步骤进行安装：

\1. 克隆仓库
\   ```bash
\   git https://github.com/example/repo.git

进入目录
\cd repo

安装依赖
\npm install
npm install <依赖名称>

使用方法的实例
def main():
    print("Hello, World!")

if __name__ == "__main__":
    main()

有时候写完一些自述会发现没有换行
现在解决方法有，在末尾加两个空格  
在结尾加<br> 使用HTML的换行标签 <br>
使用空行

以上几种方式

##文件中的各种编辑
[文件位置截图](![image](https://github.com/user-attachments/assets/dea257bb-f671-43b6-bf01-f7cf0ef40354)
) 文件这里可以创建许多东西，我们可以再创建一个.md

并且之间可以使用超链接来关联


使用 package.json 管理依赖
通常，我们会在 package.json 文件中定义项目所需的所有依赖，然后用户只需运行 npm install 就能一次性安装所有依赖。

创建或编辑 package.json
可以手动创建一个 package.json 文件，或者使用 npm init 命令生成一个：  
npm init  
生成的 package.json 文件中可以包含所有项目依赖：

使用GitHub Pages
GitHub Pages是一项免费服务，可以将你的仓库内容托管为静态网站，非常适合用来发布博客、文档或个人网站。
[创建pages](![image](https://github.com/user-attachments/assets/1622412e-970f-4465-ae13-a3c3fe1f2d6c)
)  找到设置
再找到[pages](![Uploading image.png…]()
)
