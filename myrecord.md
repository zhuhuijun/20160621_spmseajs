# spm init 命令可以初始化一些文件目录
---
命令行工具路径切换至 util/ ，运行：

spm init

spm 会在 util/ 中创建以下文件：

util/
	examples/
	src/
	tests/
	package.json
	README.md

其中：

    examples/ 用于存放演示文件。
    src/ 为模块源码，打包后的文件会存放到和 src/ 平级的 dist/ 目录下。
    test/ 用于存放测试用例，你可以使用 jasmine 等工具来保障代码的质量。
    package.json 为本模块打包部署的配置。

---
