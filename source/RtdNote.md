# 使用ReadTheDocs构建托管技术文档

## 前置准备

1. ReadTheDocs 账号
2. Github（Gitee）账号
3. Python环境（如anaconda3）
4. Typora（最后一个免费版本 0.11.18）



Github新建项目

在github（gitee）上新建项目，如ReadTheDocsNote



## Sphinx安装与测试



打开Anaconda Prompt 

![image-20220615141517804](assets/images/image-20220615141517804.png)

安装Sphinx

```bash
pip install sphinx
```

构建项目文档

```bash
# 将刚才在github（gitee）新建的项目，克隆到本地
git clone git@gitee.com:dimwalker/ReadTheDocsNote.git
# 切换目录
cd ReadTheDocsNote
# 创建项目
sphinx-quickstart
```

按提示设置文档信息

