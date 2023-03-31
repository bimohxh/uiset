


<p align="center">
    <img src="logo.svg" />
</p>


<p  align="center">A high-quality, free and commercially available UI resources. anyone can recommend.</p>
<p  align="center">
<img src="https://img.shields.io/github/issues-pr-raw/bimohxh/uiset?label=pull%20request" />
    <img src="https://img.shields.io/github/license/bimohxh/uiset" />
    <a href="README.zh.md"><img src="https://img.shields.io/badge/%E4%B8%AD%E6%96%87-%E8%AF%B4%E6%98%8E-orange" /></a>
</p>

# Category


- [**😃 Emoji**](categorys/emoji) 
- [**🖼️ Image**](categorys/image)
- [**🎨 Color**](categorys/color)
- [**🏳️‍🌈 Icon**](categorys/icon)
- [**🌫️ Pattern**](categorys/pattern)
- [**💡 Illustration**](categorys/illustration)
- [**🎉 Beautify**](categorys/beautify)
- [**🤠 Avatar**](categorys/avatar)
- [**✒️ Font**](categorys/font)



# Submit

Clone this project, then create a new directory under `categorys/[category]`, add the following two files and create a pr

1、`meta.json` (Required) The information used to describe the resource, the format is as follows

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

- `name`: Resource name, required.
- `summary`: An english brief description of the resource, required。
- `summary_zh`: A chinese brief description of the resource, required。
- `website`: Resource website address, required.
- `github`: The GitHub open source address of the resource, optional.
- `license`: Resource license agreement, optional (`name` and `url` must be filled in at least one)。
    - `name`: License name.
    - `url`： License address.
- `payload`: optional
    - `count`： Quantity, such as the number of icons and illustrations
- `tags`: custom tags


2、`thumbnail.png` (*Required) Thumbnail, recommended size `300 * 300` px, please use https://tinypng.com/ to compress the thumbnail.
