<div align="center">
  <img src="https://image.ibb.co/h6visf/music-player.jpg" width="50%"/>
	<br/>
</div>

## 简介
一款开源的基于网易云音乐api的在线音乐播放器。具有音乐搜索、播放、下载、歌词同步显示、个人音乐播放列表同步等功能。

MusicPlayer是一款开源的基于网易云音乐api的在线音乐播放器。具有音乐搜索、播放、下载、歌词同步显示、个人音乐播放列表同步等功能。
前端界面参照QQ音乐网页版进行布局，同时采用了流行的响应式设计，无论是在PC端还是在手机端，均能给您带来原生app般的使用体验。

## 界面欣赏
![](https://image.ibb.co/dzGWv0/1.jpg)
![](https://image.ibb.co/jYZvNf/2.jpg)

## 更新日志
v2.41 2018/3/13
* 修复 IE 下播放键错位的 BUG
* 修改默认背景为黑色
* 其它一些细节优化

v2.4 2018/3/11
* 修复网易云音乐无法播放
* 增加标题栏滚动效果(感谢@lzcykevin)
* 增加歌曲循环播放控制(感谢@yuxizhe)
* 修复百度音乐无法播放
* 优化连续播放失败的歌曲过多时，自动终止播放。防止卡死
* 压缩图片素材，限制封面图片尺寸，优化页面加载速度

v2.32 2017/9/15
* 修复播放历史记录歌曲时播放失败的 BUG
* 新增播放歌曲时浏览器标题栏显示相关信息
* 一些细节的完善

v2.31 2017/9/13
* 优化下载功能，支持直接弹出下载
* 下载或分享无版权音乐时给出提示
* 再次降低移动端背景特效内存占用
* 修复某些手机浏览器列表页右侧菜单按钮下移 BUG
* 升级 Meting 至最新版本

v2.3 2017/9/9
* 全面支持网易云、QQ、虾米、酷狗、百度音乐源切换
* 移动端歌曲列表支持直接分享、下载歌曲
* 降低内存占用，解决移动端背景特效卡顿问题
* 新增对 https 的支持(酷狗、百度音乐源除外)
* 新增运行环境自检功能
* 优化中等屏幕下显示效果
* 修复长歌词定位错乱的 BUG
* 修复无法获取自定义专辑封面的 BUG
* 修复移动端无法自动播放下一曲的 BUG
* 修复切换播放列表后滚动条未归位的 BUG
* 修复某些情况下歌词与歌曲不对应的 BUG
* 修复中小屏幕下顶部 tab 激活错乱的 BUG
* 修复搜索分页的 BUG
* 去除超时检测

v2.21 2017/5/19
* 临时修复 API 失效问题
* 新增歌曲超时检测，播放超时则自动播放下一首
* 新增设置数据传输方式(GET/POST)
* (这是一个临时版本，虽然解决了一部分API失效的问题，但是还是存在一些问题。剩下的问题将在之后的 v2.3 正式版中解决)

v2.2 2017/3/26
* 用户歌单获取时新增加载中动画及遮罩，防止重复加载
* 修复中等屏幕下鼠标滑过tab边框消失的 BUG
* 修复某些情况下第一句歌词无法渲染的 BUG
* 修复在IE9下音乐无法播放的 BUG
* 更换背景展现方式，整体界面更美观
* 正在播放和播放历史列表支持一键清空
* 新增图片加载失败时替换处理
* 新增小屏幕下为当前显示的tab添加下划线
* 新增favicon小图标
* 新增歌曲播放时进度条小点闪烁效果
* 优化后台数据获取失败时弹出提示
* 其它的一些细节优化

v2.1 2017/3/20
* 紧急修复部分浏览器下切换歌曲造成无限播放失败循环的 BUG
* 新增点击未加载完的播放列表弹出提示
* 新增搜索时弹出加载中动画
* 切换歌曲后进度条自动复位
* 优化歌曲外链显示方式，方便复制
* 优化封面图像加载大小
* 新增无歌词、歌词加载中提示
* 优化歌词展现方式

v2.0 Beta 2017/3/18
* 所有代码均推翻重写，前端界面全新改版
* 完善对手机端的适配，新支持 IE9~IE11 浏览器
* 修复 IE11 下点击下载歌曲名字乱码的 BUG
* 新增“正在播放”、“播放历史”列表功能
* 新增后台自定义播放列表功能，支持多种列表定义模式
* 新增本地记录用户设置及播放列表功能
* 进度条支持响应点击事件

## 注意事项
`关于API文件`

由于网易云音乐官方封锁了国外的访问，因此本播放器的 api.php 在海外的空间上可能无法运行(其实有个“你懂的”的功能，请自行挖掘)，建议在国内空间使用。

`关于兼容性`

本播放器设计支持 IE9及以上的现代浏览器。并且已在 Chrome、firefox、IE11 等浏览器测试使用正常。

`关于版权`

本播放器由 mengkun(http://mkblog.cn) 开发，欢迎各位移步到他的博客。

`关于歌曲`

播放器中采用了 网易云音乐(http://music.163.com/) 的 api，因此相对应的歌曲版权归网易云音乐所有。支持正版音乐，请使用官方版网易云。

## 项目地址
在线演示：http://lab.mkblog.cn/music/  
详细介绍：https://mkblog.cn/757/  
GitHub：https://github.com/mengkunsoft/MKOnlineMusicPlayer  
百度网盘：http://pan.baidu.com/s/1gfkbAef  

## 感谢
最后必须感谢这款开源播放器的源码贡献者--孟坤。[孟坤博客](https://mkblog.cn/757/)
