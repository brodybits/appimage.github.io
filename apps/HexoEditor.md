---
layout: app

permalink: /HexoEditor/
description: This is markdown editor for Hexo.
license: GPL-3.0

screenshots:
  - HexoEditor/screenshot.png

authors:
  - name: zhuzhuyule
    url: https://github.com/zhuzhuyule

links:
  - type: GitHub
    url: zhuzhuyule/HexoEditor
  - type: Install
    url: https://github.com/zhuzhuyule/HexoEditor/releases

desktop:
  Desktop Entry:
    Name: HexoEditor
    Comment: This is markdown editor for Hexo.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: hexoeditor
    X-AppImage-Version: 1.1.10
    X-AppImage-BuildId: be73bbb0-f456-11a7-09c5-37d1678bd864
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  main: app/index.js
  repository:
    type: git
    url: git+https://github.com/zhuzhuyule/HexoEditor.git
  author: Menci,zhuzhuxia  <zhuzhuyule@126.com> (http://zhuzhuyule.com/)
  license: GPL-3.0
  homepage: https://github.com/zhuzhuyule/HexoEditor#readme
  dependencies:
    biu.js: "^1.2.0"
    bluebird: "^3.5.1"
    cheerio: "^1.0.0-rc.2"
    codemirror: "^5.18.2"
    configstore: "^2.1.0"
    electron-localshortcut: "^0.6.1"
    electron-titlebar: 0.0.2
    flowchart.js: "^1.6.3"
    font-awesome: "^4.6.3"
    hexo-front-matter: "^0.2.3"
    hexo-fs: "^0.2.2"
    hexo-renderer-ejs: "^0.3.1"
    hexo-renderer-marked: "^0.3.0"
    hexo-renderer-stylus: "^0.3.3"
    hexo-util: "^0.6.2"
    highlight.js: "^9.6.0"
    jquery: "^3.1.0"
    js-sequence-diagrams: "^1000000.0.6"
    katex: "^0.6.0"
    lodash: "^4.15.0"
    lrucache: "^1.0.2"
    mathjax: "^2.6.1"
    mathjax-node: "^0.5.1"
    mime: "^1.3.4"
    moemark: "^0.3.8"
    moment-timezone: "^0.5.14"
    nunjucks: "^3.0.1"
    os-locale: "^1.4.0"
    raphael: "^2.2.1"
    strip-indent: "^2.0.0"
    swig: "^1.4.2"
    swig-extras: 0.0.1
    titlecase: "^1.1.2"
    util: "^0.10.3"
    yamljs: "^0.3.0"
---
