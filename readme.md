## 1. 安装依赖
```shell
npm install
```
## 2. 本地测试
```shell
window系统:
npm run dev:Win
mac系统：
npm run dev:Mac
```
- 本地开发生成文件放在node文件夹中的modified文件中
- 用法讲解：
  - 1. vscode使用正则表达式 @\{\w*\}[^@] 查询可以看哪些不是以 @{}@  规格的字符。
  - 2. 在源文件修改链接。然后npm run dev:Win。会在node/modified文件生成最终变更的文件。
  - 3. 可以通过现网查询 @{ 开头两个关键字，查询是否有key没有被替换。