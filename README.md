# 关于

该repo用于存放与UI相关的免费资源信息，有效分类参见：https://github.com/uiset-com/generate/blob/master/data/category.json
# 提交资源

clone本项目，然后在 `categorys/[分类]` 下面新建一个目录，添加下面两个文件再提 pr

1、`meta.json` 用来描述资源的信息，格式如下

```json
{
    "name": "Lucide",
    "summary": "好看的SVG图标",
    "website": "https://lucide.dev/",
    "github": "https://github.com/lucide-icons/lucide"
}
```
其中 `github` 为可选参数，其它为必填参数


2、`thumbnail.png` 缩略图，宽度小于800px，请用 https://tinypng.com/ 对缩略图进行压缩。
