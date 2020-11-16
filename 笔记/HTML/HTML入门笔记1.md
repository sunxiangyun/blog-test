# HTML 入门笔记 1

### 1.HTML 是谁发明的

HTML 是由一名叫 Tim Berners-Lee 的科学家发明的.

### 2.HTML 起手应该写什么

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

### 3.常用的表章节的标签有哪些，分别是什么意思

1.h1~h6 章节标题，字体依次变小<br>
2.select 章节<br>
3.article 文章<br>
4.main 主要内容<br>
5.p 段落<br>
6.header 头部<br>
7.footer 脚部<br>
8.aside 旁支内容<br>
9.div 容器<br>

### 全局属性有哪些

1.class<br>
2.contenteditable 可编辑，可以与 style 属性等配合使用，用作编辑器<br>
3.hidden<br>
4.id 一般不要使用，多个相同 id 不会报错<br>
5.style 优先级高于 css，小于 js 设置的<br>
6.tabindex 按下 tab 键访问，tabindex 可以是正数，不必是连续的，若正数按从小到大顺序访问，0 为最后访问，-1 为不访问<br>
7.title <br>

### 常用的内容标签有哪些，分别是什么意思

1.ol+li 有序列表<br>
2.ul+li 无序列表<br>
2.dl+dt+dd <br>
4.pre (preview 的缩写)此标签下内容空格全都保留<br>
5.hr 分隔线<br>
6.br 换行<br>
7.a 超链接<br>
8.em 斜体<br>
9.strong 表示本身很重要，加粗<br>
10.code 标签里面可写代码，字体等宽，可与 pre 配合使用（pre+code）<br>
11.q quote 不换行引用（内联引用）<br>
12.blockquote 可换行的引用（块引用）<br>
