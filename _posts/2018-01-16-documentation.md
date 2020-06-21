---
title: 主题使用文档
---

## 1. 搭建过程

1. [GitHub](https://github.com) ：申请 GitHub 账号存放你的博客内容。 
2. [GitHub Desktop](https://desktop.github.com/) ：GitHub Desktop 软件实现本地仓库和 GitHub 服务器仓库的同步。
3. [Jekyll Docs](https://jekyllrb.com/) ：博客搭建的一些相关知识。
4. [Jekyll themes](https://jekyllthemes.org/) ：Jekyll 的主题网站，说不定里面有一些你喜欢的主题。
5. [GitHub 官方指导](https://help.github.com/cn/github/working-with-github-pages)。

## 2. 排版

这里使用 GitHub 默认布局，因此样式也是遵循 GitHub 的，如下

### 2.1 图片

![图片样例]({{ site.img }}/example.jpg)

### 2.2 引用

> 我思故我在 -- 笛卡尔

### 2.3 代码段

``` c++
#include <iostream>

using namespace std;

int main(){
  cout << "Hello World!";
  return 0;
}
```

### 2.4 字体

- **粗体**
- *斜体*
- `高亮`
- ~~删除~~
- <u>下划线</u>

### 2.5 表格

| name  | ID   | score |
| ----- | ---- | ----- |
| David | 1    | 98    |
| Nancy | 2    | 99    |
| Curry | 3    | 101   |

### 2.6 数学公式

如果你的文章需要数学公式渲染，添加 Liquid 标签 {% raw %} `{{ site.math }}` {% endraw %} 到文章末尾。

$$
\frac{\mathrm{d}}{\mathrm{d}t} \left ( \frac {\partial L}{\partial \dot{q}_j} \right ) = \frac {\partial L}{\partial q_j}
$$

### 2.7 视频

<video src="https://cdn-video.xinpianchang.com/5b7fc02a84108.mp4" width = "100%" controls preload></video>

## 3. 附加功能

GitHub 官方支持了一些 Jekyll 插件，具体查看 <https://pages.github.com/versions/>，下面是本主题用到的一些插件。

### 3.1 github 表情

:smile:

### 3.2 mentions

@professordeng

### 3.3 图片

{% avatar professordeng %}
{% avatar ericclose %}

{{ site.math }}