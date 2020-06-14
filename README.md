# 简答题
## 1、
前端工程化让前端开发结束刀耕火种的时代，让前端自成体系，更具价值。工程化主要包含这四个方面：模块化、组件化、规范化、自动化。  
（1）可以使用es6最新特性进行代码开发工作，不用在考虑兼容问题，webpack+babel会自动完成代码的转换  
（2）可以使用SASS、LESS等预处理编译语言，工程化配置相关loader会轻松的完成css的编译工作  
（3）实现前后端分离，不在依赖后端提供的接口，轻松实现mock数据  
（4）代码风格统一，减少重复工作，提高开发效率  
（5）自动化打包构建发布


## 2、
脚手架还提供了项目的规范与约定，使项目组织结构更清晰统一、开发更加规范，针对相同类型项目直接生成相同的模块依赖、工具配置、基础代码，提高工作效率。

# 编程题
## 1、
1. 初始化package.json文件，并添加bin字段指定cli入口文件 ， yarn link把模块链接到全局  
2. 通过命令行交互询问用户问题，使用inquirer，根据用户回答的结果下载创建好的模板文件，最终把脚手架发布到npm