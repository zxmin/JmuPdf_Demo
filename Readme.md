## 依赖JmuPdf，支持pdf/xps转换为图片的小程序 ##
### 目录清单： ###
lib（项目引入jar包及dll文件）
src（源代码）
jmupdf.7z（jumpdf工具包，存档用）

### 注意事项： ###

- 直接编译就可以跑程序了，注意代码里面的路径配置，需要有对应的转换文件（代码中使用了F：\）
- 记得要把配置java.library.path，为了让程序发现*.dll*文件用的