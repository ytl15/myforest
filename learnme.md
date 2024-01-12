# hugo server --buildDrafts
    在线渲染



create new _index page for content/dir1/dir2/

"hugo new dir1/dir2/_index.md"

text go into the index.md file show up in the list page.


# 在archetype 调节每页模版


# shortcode

add youtube links 
{{< youtube 2xkNJL4gJ9E >}}
{{< youtube peplMWeIn30 >}}

go to hugo doc to check more


# using template
(tutoriol 11)
template stored in the layout folder.


# section template

使得 poem 里的内容模版 和 essay 里不一样
在 layout 里建立 /poem/
overwrite single/list ...

# Base Templates (Tutorial 16)
建立在 layouts. 文件夹里，baseof.html


# Variables

a.md
myVar = "aaa"

在模版中调用这个
{{ .Params.myVar }}

可以赋值value，后续使用
{{ $myVar := 1}}
{{ $myVar }}
调用颜色：
<h1 style ="color:{{ .Params.color}}> SingleTemplate



https://lbqaq.top/p/blog%E5%B8%B8%E7%94%A8%E7%9A%84%E5%91%BD%E4%BB%A4/
