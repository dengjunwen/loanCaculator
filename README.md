这是一个ionic写的贷款计算器，适合消费金融的短期贷款。 
适用于android  iOS   h5
 - 支持自定义年利率 月利率 日利率，并且根据日利率计算年利率，以此类推
 - 支持等额本息、等额本金热切换
 - 最小支持一个月的贷款

  
如图所示
![此处输入图片的描述][1]

使用方式：

 - 需要提前安装ionic的环境。去搜索ionic的环境安装教程吧。
 - 使用命令行`git clone https://github.com/dengjunwen/loanCaculator.git`
   或者下载下来。
 - 进入项目的根目录，执行`ionic serve`，输入localhost，即可在浏览器中看到运行的网页。
 - 按照ionic的教程，分别添加android和ios平台。(所有都是在项目的根目录进行的)  

&nbsp;&nbsp;&nbsp;&nbsp;iOS:
<pre>
    ionic platform add ios  
    ionic build ios  
    ionic emulate ios
</pre>

&nbsp;&nbsp;&nbsp;&nbsp;android:
<pre>
    ionic platform add android  
    ionic build android  
    ionic emulate android
</pre>

  [1]: https://raw.githubusercontent.com/dengjunwen/loanCaculator/master/loadCaculator.gif