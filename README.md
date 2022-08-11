# 关于

该repo用于存放与UI相关的免费资源信息，有效分类参见：https://github.com/uiset-com/generate/blob/master/data/category.json
# 提交资源

clone本项目，然后在 `categorys/[分类]` 下面新建一个目录，添加下面两个文件再提 pr

1、`meta.json`（必选） 用来描述资源的信息，格式如下

```json
{
    "name": "Lucide",
    "summary": "好看的SVG图标",
    "website": "https://lucide.dev/",
    "github": "https://github.com/lucide-icons/lucide",
    "license": {
        "name": "ISC",
        "url": "https://github.com/lucide-icons/lucide/blob/main/LICENSE"
    }
}
```

- `name`: 资源名，必填。
- `summary`: 资源简述，必填。
- `website`: 资源网站地址，必填。
- `github`: 资源的GitHub开源地址，选填。
- `license`: 资源的使用许可协议，选填（`name` 和 `url` 至少必须填写一个）。
    - `name`: 协议名
    - `url`： 协议地址


2、`thumbnail.png`（必选）缩略图，推荐尺寸 500 * 360 px，请用 https://tinypng.com/ 对缩略图进行压缩。

3、`README.md`（可选）关于资源的详细说明和使用说明，markdown 格式，最终会以相似的效果渲染到uiset的资源详情页中，参考 https://uiset.com/resource/illustration/undraw
