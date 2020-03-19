# [MUJIN Controller API](https://mujin.github.io/mujincontrollerapiraml/)

## Prerequisites

```bash
npm install -g raml2html
```

## Build

```bash
raml2html --input api.raml --validate
mkdir -p ./build/en ./build/ja ./build/zh
raml2html --input api.raml --output ./build/en/index.html --extensionsAndOverlays api_en.raml
raml2html --input api.raml --output ./build/ja/index.html --extensionsAndOverlays api_ja.raml
raml2html --input api.raml --output ./build/zh/index.html --extensionsAndOverlays api_zh.raml
```
