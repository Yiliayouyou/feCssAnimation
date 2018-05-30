#步骤一：安装破解版AE
具体操作自行度娘~
#步骤二：安装AE第三方插--bodymovie
1.下载https://github.com/airbnb/lottie-web zip包；得到lottie-web/build/extension/**bodymovin.zxp**
2.下载bodymovin.zxp安装工具exman-com-line-tool 
https://technologypartners.adobe.com/home/support/exman-com-line-tool.html
3.将bodymovin.zxp放入exman-com-line-tool文件夹下
4.以管理员身份打开cmd，进入到exman-com-line-tool所在文件夹下
5.运行命令ExManCmd.exe /install bodymovin.zxp；如果成功会有提示；同时AE软件中 窗口-->扩展下会出现bodymovie插件
6.打开AE，在编辑-->首选项-->常规下，选中“允许脚本写入文件和访问网络”并保存
参考文档：https://github.com/airbnb/lottie-web
#步骤三：通过AE导出动画json文件及js文件
1.打开一个动效项目
2.窗口-->扩展-->bodymovie
3.选中一个合成后的图层，选择要保存文件的目录，选择导出，完成后在指定目录下出现相应的json文件
4.GetThePlayer生成相应的js文件
#步骤四：web端在模板文件中使用
https://github.com/airbnb/lottie-web