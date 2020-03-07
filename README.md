#本工程记录学习OpenGL的过程。

##xcode command line工程

###前期xcode配置
1.安装brew
2.安装glfw，glew库
3.下载glad库
4.在项目中framework依赖中添加glfw，glew和opengl库
5.在项目中search路径添加head：/usr/local/include，在lib：/usr/local/lib
6.项目中导入glad.c文件


一个网格最少需要什么数据。一个网格应该至少需要一系列的顶点，每个顶点包含一个位置向量、一个法向量和一个纹理坐标向量。一个网格还应该包含用于索引绘制的索引以及纹理形式的材质数据（漫反射/镜面光贴图）。
