# Changelog

## [1.1.1](https://github.com/MEMLTS/NetEaseMusicMeta/compare/v1.1.0...v1.1.1) (2025-06-26)


### ♻️ 代码重构

* **index:** comment out unused console logs and add getSong import ([039a446](https://github.com/MEMLTS/NetEaseMusicMeta/commit/039a446e6d04f709943b72d8517d00dc1a8aaab5))
* **netease/player:** simplify song response handling ([ea2ae88](https://github.com/MEMLTS/NetEaseMusicMeta/commit/ea2ae886f799314258aa6f90f8bbbaf5feffcf86))
* **netease:** improve type safety and clean up unused code ([6dcad96](https://github.com/MEMLTS/NetEaseMusicMeta/commit/6dcad96c1ba367e2d1971d9dbc38c877be67732b))
* update issue template for Bun support ([2dd018c](https://github.com/MEMLTS/NetEaseMusicMeta/commit/2dd018c6a2f1335d0bf959df4f3082fa899ac073))


### 🎡 持续集成

* improve ChatGPT Code Review workflow ([8da55a0](https://github.com/MEMLTS/NetEaseMusicMeta/commit/8da55a0dea662ca05094953024e3a52f31922c9b))
* 更新代码审查工作流和模型函数 ([b749537](https://github.com/MEMLTS/NetEaseMusicMeta/commit/b7495370291d39a2fcfeb015b5a94d711c8bb648))

## [1.1.0](https://github.com/MEMLTS/NetEaseMusicMeta/compare/v1.0.0...v1.1.0) (2025-06-24)


### ✨ 新功能

* add CodeQL scanning workflow ([7f74366](https://github.com/MEMLTS/NetEaseMusicMeta/commit/7f74366a064828f78b6c5c86f80ae4fccd887517))
* **index:** 添加获取评论功能并进行测试 ([960956c](https://github.com/MEMLTS/NetEaseMusicMeta/commit/960956c4d83dd48ba8db63af24bc7e4295a6ec29))
* **models:** 添加 NetEase 音乐模块的导入和导出 ([63227ef](https://github.com/MEMLTS/NetEaseMusicMeta/commit/63227efd173f7ad384a5fc95ed336073f3ae2af4))
* **utils:** 添加 ffmpeg 模块的导入 ([23ea290](https://github.com/MEMLTS/NetEaseMusicMeta/commit/23ea290139ef2a378a84559d91bb81038bc236a5))
* 初始化 neteasemusicmeta 项目 ([66868f1](https://github.com/MEMLTS/NetEaseMusicMeta/commit/66868f19ed00d61ac861b47d572c1c8bdd9101d7))
* **添加 FFmpeg 处理音频元数据:** feat(添加 FFmpeg 处理音频元数据):  ([b0ccc94](https://github.com/MEMLTS/NetEaseMusicMeta/commit/b0ccc948696e5f621a1f7dd6d82cc1ea81ebb9cb))


### 🐛 错误修复

* **models:** 优化错误提示信息 ([5ff6dc5](https://github.com/MEMLTS/NetEaseMusicMeta/commit/5ff6dc59a6561f17e69fcd320d1684fbad7053c5))
* **release-please:** 修改配置以禁用组件标签并更新中文描述 ([fedd1fd](https://github.com/MEMLTS/NetEaseMusicMeta/commit/fedd1fdb7b12a200502b2bca335ac919bc15d9b9))


### 📝 文档更新

* 添加 issue 模板以规范化问题提交 ([ff6a3cc](https://github.com/MEMLTS/NetEaseMusicMeta/commit/ff6a3cc8f3a851eae25eb73f1cb9df4b2a4d42dd))


### ♻️ 代码重构

* **ffmpeg:** 注释掉歌词文件创建逻辑 ([033d669](https://github.com/MEMLTS/NetEaseMusicMeta/commit/033d66959419dfeda5a53518410fb540f46328c4))
* **index:** 重构代码并添加搜索功能 ([fdfbf4c](https://github.com/MEMLTS/NetEaseMusicMeta/commit/fdfbf4c98a06a71a90d689e90a8d3897230d52ce))
* **models:** 移除未使用的变量 ([e6c0de1](https://github.com/MEMLTS/NetEaseMusicMeta/commit/e6c0de1afda18a3b08f3972ad485c3e1e6775af6))
* **models:** 移除歌曲详情中的专辑封面字段 ([91e80fb](https://github.com/MEMLTS/NetEaseMusicMeta/commit/91e80fb335c5bc8efd596e709c062d839eb17dd1))
* **netease:** 为 search 函数添加 JSDoc 注释 ([99738d8](https://github.com/MEMLTS/NetEaseMusicMeta/commit/99738d8979a68326fedca1af87477075fd61fc56))
* **netease:** 移除未使用的 sign 模块导入 ([99baded](https://github.com/MEMLTS/NetEaseMusicMeta/commit/99baded513eaa4fac9f2367ac568d5f8d7b7e51f))


### 📦️ 构建系统

* **release:** 更新 release-please 配置 ([1780106](https://github.com/MEMLTS/NetEaseMusicMeta/commit/1780106beb638e76262f2641600615cc35898d1f))
* 将构建命令从 Node.js 更改为使用 bun ([349c8a7](https://github.com/MEMLTS/NetEaseMusicMeta/commit/349c8a7b9f356bf871e02bddeb09f6d29be09e7f))
* 添加版本号 ([68c89dc](https://github.com/MEMLTS/NetEaseMusicMeta/commit/68c89dc58abc3dd073fdbe8fad5ec4ff7056ee57))


### 🎡 持续集成

* 更新 release workflow 权限设置 ([513e579](https://github.com/MEMLTS/NetEaseMusicMeta/commit/513e5799c7ac41e13777d56109bca9b49b8934c7))
* 移除 CodeQL 工作流 ([5db5406](https://github.com/MEMLTS/NetEaseMusicMeta/commit/5db5406c3a3d2eef09c6ed08ac0b31a1af057ffe))
