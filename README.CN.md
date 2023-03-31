


<p align="center">
    <img src="logo.svg" />
</p>


<p  align="center">一个收集优质免费可商用 UI 资源的开源仓库，任何人都可以推荐。</p>
<p  align="center">
<img src="https://img.shields.io/github/issues-pr-raw/bimohxh/uiset?label=pull%20request" />
    <img src="https://img.shields.io/github/license/bimohxh/uiset" />
</p>

# 分类


- [**😃 表情**](categorys/emoji)
- [**🖼️ 图片**](categorys/image)
- [**🎨 配色**](categorys/color)
- [**🏳️‍🌈 图标**](categorys/icon)
- [**🌫️ 图案**](categorys/pattern)
- [**💡 插画**](categorys/illustration)
- [**🎉 美化**](categorys/beautify)
- [**🤠 头像**](categorys/avatar)
- [**✒️ 字体**](categorys/font)



# 提交资源

clone本项目，然后在 `categorys/[分类]` 下面新建一个目录，添加下面两个文件再提 pr

1、`meta.json`（必选） 用来描述资源的信息，格式如下

```json
{
    "name": "Lucide",
    "summary": "A good iconset",
    "summary_zh": "一个好看的图标集",
    "website": "https://lucide.dev/",
    "github": "https://github.com/lucide-icons/lucide",
    "license": {
        "name": "ISC",
        "url": "https://github.com/lucide-icons/lucide/blob/main/LICENSE"
    },
    "payload": {
        "count": 10
    },
    "tags": ["Materia Design"]
}
```

- `name`: 资源名，必填。
- `summary`: 英文资源简述，必填。
- `summary_zh`: 中文资源简述，必填。
- `website`: 资源网站地址，必填。
- `github`: 资源的GitHub开源地址，选填。
- `recommend`: 是否极力推荐（布尔值，选填）
- `license`: 资源的使用许可协议，选填（`name` 和 `url` 至少必须填写一个）。
    - `name`: 协议名
    - `url`： 协议地址
- `payload`:
    - `count`： 数量，比如图标和插画数量
- `tags`: 自定义的标签


2、`thumbnail.png`（必选）缩略图，推荐尺寸 300 * 300 px，请用 https://tinypng.com/ 对缩略图进行压缩。
