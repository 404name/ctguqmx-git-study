中文   |   [English](./README-EN.md)

<h1 align="center"> 🚀启明星Git学习 </h1>
<h4 align="center"><a href="https://#" target="_blank">基础github学习学习+实践</a></h4>
  
<div align="center">

|入门及规范|提交测试|版本管理|Code Review| 冲突解决 |参与开源 |
| :---------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------: | :-------------------------------------------------------------------: | :----------------------------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------:  |
| [☁️](./Lv1小白入门) | [💻](./Lv2提交测试) | [💾](./Lv3版本管理) | [🎨](./Lv4代码审查) | [🔧](./Lv5冲突解决) | [🐍](./Lv6参与开源) | 

</div>

---
<h1 align="center"> ☁️ 仓库食用手册</h1>



## 如何使用
- 对于**每个同学**，都可以按照顺序依次去板块内完成对应的任务，如何进入下一个板块，每个板块不仅仅是学习基础知识还需要进行实战。
- 对于**高年级**的同学建议是都参与进来，尽量多贡献代码，给低年级同学提供规范，锻炼自己
- 每个模块尽量都加一些**模拟实战**的小项目，来进行实战
- 虽然是本项目是试验场，但**不欢迎不兜底的进行提交**，对自己代码负责对仓库负责
- 但**同时出问题了更好**，本项目后面阶段会故意人为制造问题，需要每位同学都参与并且能利用git版本进行修复

## 开发规范
**1. 提交须知**：`禁止提交1MB以上的大文件！！！` 
**2. 常用提交参考**：commit备注信息必须参考下面示例

```
feat：新增xxx新功能

fix：修复xxx功能，如果是修复issue记得备注issue号

docs：修改文档；

refactor：代码重构，未新增任何功能和修复任何bug；

test：测试用例的修改；
```

**3. [基于插件规范提交](https://blog.csdn.net/qq_39996837/article/details/91345528)**

- 全局性安装[commitizen](https://github.com/commitizen/cz-cli) (框架): `npm install commitizen -g` 
- 项目目录内使用该插件 `commitizen init cz-conventional-changelog --save --save-exact
` （第一次执行即可）
- 使用`git cz` 替代之前的 `git commit`这时候插件会要求你按照规范提交  
- 同时记得不要动`.gitignore` ,他会自动忽略该插件本地目录`node_modules`以及`package.json`提交，


## 项目提交忽略目录清单
```
node_modules //git提交规范插件依赖
package.json 
package-lock.json
```

## 贡献者
<a href="https://github.com/Enlightened-Star-Studio/ctguqmx-git-study/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Enlightened-Star-Studio/ctguqmx-git-study" />
</a>
