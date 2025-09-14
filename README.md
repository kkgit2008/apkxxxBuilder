## ⚠️如需使用此开源代码，请标记来自'#kkgit2008'，搬砖是个体力活，请给与尊重，谢谢！
## ⚠️If you wanna use the open source code in this repo, mark the user name '#kkgit2008'. Please respect others and achievement of working! Thanks!

* 
* 
* 



# 🔥🔥新增以下功能:

* 🔥1.通用型yml文件，支持在当前仓库构建apk，也可选择在仓库的子目录中构建 <a href=".github/workflows/build_currentRepo.yml.txt">file</a>

* 🔥2.自动上传apk文件到release页面，无需手动上传 <a href=".github/workflows/UploadApk_To_ReleasePage.yml.txt">file</a>

* 🔥3.教程: 可任意自行签名apk文件 <a href="HowToSignMyApk/">file</a>

* 🔥4.可将其他仓库作为子模块 <a href=".github/workflows/buildWithSubmodule.yml.txt">file</a>

<br> </br> 



# 🔥🔥<a href="./project-to-build">project-to-build</a>使用方法：  
  
1 将 project-to-build 内容更改为待打包的项目地址（ 如 https://github.com/kkgit2008/TVBoxOS ） 
 
2 依次点击 Actions - All workflows - apk_build001 - run workflow - run 
 
3 刷新页面，然后等待黄点变成绿点 
 
4 变绿后刷新页面，apk文件在页面右下角 

QA:
如果编译出错，可以尝试修改“.github/workflows/build.yaml”中的所有版本号，如“uses: actions/checkout@v2”. 


<br> </br> 


 

 
其他说明： 
 
该仓库是使用 Github Action 自动编译 Android 项目的一种展示。具体解释可见下面的文章：
 
[《更新慢、弃坑了？实现 Android 应用自给自足：GitHub Actions 编译实例》](https://sspai.com/post/70427)
 
如果这篇文章帮到了你，不妨回来点个赞。


<br> </br> 
<br> </br> 
