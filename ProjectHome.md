<table><td><h1>NGE2</h1>--<b>NGE</b>'s <b>N</b>ot a <b>G</b>ame <b>E</b>ngine.</td><tr><td><img src='http://topoc.googlecode.com/files/nge2logo.png' /></td></tr></table>
nge2（nge是not a game engine的递归缩写，nge第一版原为制作中国象棋psp所写，第二版得到了更全面的强化）是psp/win开发的一个程序库，不是一个游戏引擎，设计思想是简单易用，用来做各个显示程序或者游戏引擎，nge2追求的是性能，所以全部用的c函数写，而显示函数也分为各个性能要求，提供不同的显示函数。
nge2的设计就是让开发人员不需要用psp调试就能开发出psp的应用程序。就是说在windows下调试，在psp上运行。
大大降低了psp调试程序浪费的时间。

libnge2支持PSP1000，PSP2000的3xx以上版本。

libnge2采用LGPL发布源代码。使用本库建议加上nge2的logo,见图片。

以下是nge2在psp与其他方式的对比(222mhz):
<br />
<table border='1'>
<tr><th>Render</th><th>(32bit 512*512) FPS</th><th>(16bit 512*512) FPS</th></tr>
<tr><td>sdl+software render</td><td>30fps</td><td>60fps</td></tr>
<tr><td>sdl+pspgl</td><td>55fps</td><td>120fps</td></tr>
<tr><td>nge2</td><td>270fps</td><td>400+fps</td></tr>
</table>
<br />
特点：
<ol>
<li>支持16位（RGBA5650 RGBA5551 RGBA4444）/32位(RGBA_8888)显示。</li>
<li>支持JPG,BMP(24,32位),PNG,TGA（24,32位）图片读取，并转化到上述显示模式。</li>
<li>支持HZK，GBK点阵字体，FreeType字体显示。</li>
<li> 支持高效的图片缩放旋转，alpha混色效果。</li>
<li> 多种显示函数，提供不同的性能。</li>
<li>直线，矩形，三角形，圆形等几何图形的绘制。</li>
<li>音频支持，用于播放声音，mp3，wav，可扩展。</li>
<li>视频支持，用于播放动画，pmp支持。</li>
<li>支持各种图像裁剪，例如J2ME2的SetClip函数。</li>
<li>支持VC6.0，VS2003，VS2005，VS2008编译环境。</li>
</ol>
技术支持：
<ol>
<li><a href='http://www.libnge.org'>NGE2官方网站</a></li>
<li><a href='http://www.iacger.com/bbs/forumdisplay.php?f=35'>TOPOC技术支持论坛--（NGE2使用中的疑问请到这里提）</a></li>
<li><a href='http://hi.baidu.com/topoc'>TOPOC开发者博客</a></li>
<li><a href='svn://www.libnge.org/libnge2/'>最新代码下载svn://www.libnge.org/libnge2/</a></li>
</ol>

