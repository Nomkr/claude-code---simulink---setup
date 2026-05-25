# claude code + Simulink仿真自动化

首先打开网页：

[Releases · matlab/simulink-agentic-toolkit](https://github.com/matlab/simulink-agentic-toolkit/releases)

下载mltbx工具

安装好后会自动打开matlab，并显示：“安装成功”

在命令行窗口输入：

matlab.addons.toolbox.installToolbox("agenticToolkitInstaller.mltbx")

setupAgenticToolkit("install")


接下来按照自己的情况选择选项即可



如果出现报错，可能是github访问出问题了，可以过一会再试一次



安装过程中会让你做一系列选择，比如安装哪个工具包，是否安装到你的智能体工具中，你在命令行输入你的选项就行，不会了就问复制命令行的内容发给AI。这里特别提示一下：不建议选择全局安装，最好将所有 MATLAB 相关项目放在同一个文件夹下(例如D:\Documents\MATLAB)。安装时选择Aspecificproject（仅安装到特定项目），并将文件夹路径填写为 D:\Documents\MATLAB( (替换为你自己的路径）。这样，该文件夹下的所有子文件夹都能使用该配置，而其他无关项目不会受到影响，同时也能省些词元 (token) 开销。

