<p style="font-size:12px" align="center">假装这是logo</p>
<h1 align="center" dir="auto">哔哩哔哩直播小工具</h1>
<p align="center" dir="auto">
  <a><img src="https://img.shields.io/github/stars/isma123HH/bilibili_live-assistant.svg"></img></a> 
  <img src="https://img.shields.io/github/forks/isma123HH/bilibili_live-assistant.svg"></img> 
  <img src="https://img.shields.io/github/issues/isma123HH/bilibili_live-assistant.svg"></img> 
  <img src="https://img.shields.io/github/license/isma123HH/bilibili_live-assistant.svg"></img>
</p>
<p align="center" dir="auto">
  <a href="#功能介绍">功能介绍</a>
  <br>
  <a href="#功能展示">功能展示</a>
  <br>
  <a href="#更新列表">更新记录</a>
</p>

# 介绍
本项目初衷是做一个直播弹幕根据屏蔽词来屏蔽内容，发现B站做过后本应直接废弃掉，但由于在发现之前加入了不少小功能，所以我仍然决定保留并开源。大家当一个小功能脚本用就好了<br>
<b>如果你想要查看本脚本源代码，我劝你还是放弃吧。因为本脚本的源码包括但不限于存在以下要素：无用的变量、重复的代码、令人高血压的换行</b><br>
<del><b>如果执意要看，那请自备好降压药</b></del><br>
<b>如果您对此脚本有什么想法/意见，请新建一个Issues！如果您想对本脚本作出贡献，可以新建一个Issues来告诉我，我会定期查看的。</b>
# 教程
请确认浏览器已经安装<a href="https://www.tampermonkey.net/">油猴脚本</a>后<br>
<a href="https://github.com/isma123HH/bilibili_live-assistant/raw/main/build/bili_live_assistant.user.js">点我安装脚本</a> 或者前往releases自行下载导入油猴
# 功能介绍
首先说明一点，除屏蔽相关设置外，其他功能都放到了播放器的右键菜单里，所以如果你是只想用小功能，那就在播放器里面右键！<br>
还有一个没有提到的功能：<b>在每条弹幕下方标注发送时间（我觉得这个功能非常重要）</b>
<br>
## 功能列表
>小功能菜单 #使用方法:右键直播播放器即可找到本菜单
>>获取直播流(获取实时直播流)<br>
>>获取直播封面(获取当前直播间的直播封面)<br>
>><del>删除进直播间提示(已删除，这个小功能活了一个半月，很神奇吧？)</del><br>
<img src="assets/QQ截图20220518233134.png" />

>直播切片菜单(也就是直播回放流) # 选择之后会自动复制相应的回放流链接，可以粘贴至PotPlayer或其他在线网站观看
>>这里就不需要解释了吧<br>
>>300秒(5分钟)回放<br>
>>180秒(3分钟)回放<br>
>>60秒回放<br>
>>30秒回放<br>
>>15秒回放<br>
<img src="assets/QQ截图20220518233312.png" />

# 功能展示
## 弹幕屏蔽
<img src="assets/Desktop 2022.05.18 - 21.41.02.05.gif" alt="示例" /><br>
当检测到弹幕包含屏蔽词，则将屏蔽词变成:□
## 小功能菜单
<img src="assets/Desktop 2022.05.18 - 21.41.02.05_1.gif" alt="示例" /><br>
在播放器里右键即可查看本脚本提供的小功能，例如:<b>获取直播流</b>、<b>获取直播间封面</b>
<br>
## 直播切片菜单
<img src="assets/Desktop 2022.05.18 - 21.41.02.05_2.gif" alt="示例" /><br>
### 注意！这个功能并非在每一个直播间都生效！
可以获得3分钟、1分钟、60秒、30秒、15秒的直播回放流，但是流可能`有点卡顿`
## 直播流播放器
<img src="assets/live_player_show.gif" alt="示例" /><br>
复制直播流后懒得打开网站/软件观看?我们已经内置了播放器!只需要点击"插件设置"按钮,再点击"m3u8播放器"并粘贴直播流链接即可享受不跳转网页观看!<br>
小提示：使用这个播放器会将原来的播放器静音，另外，它其实可以滑动的！

# 未来计划
- [x] 在直播间页面弹出新窗口(插件设置那种的窗口)显示直播回放流。已放弃了吗？并不，这个功能已经在脚本的2.5.3版本上线! 最后推荐一个在线网站http://tool.liumingye.cn/m3u8/index.php

# 目前的问题
- [ ] 脚本加载成功后会有提示，可能会在导致提示"恭喜主播登上热门榜"的窗口里仍然显示一次提示(该窗口太小会导致排版错乱，极其影响观看体验)

# 更新列表
<ul>
<li>2022/5/21 22:47 更新脚本至2.5.3。更新内容：在"插件设置"菜单内新增了"m3u8播放器"，不需要打开其他网页即可观看直播流链接！以及删除了"删除进入直播间提示"功能</li>
<li>2022/5/21 23:37 更新脚本至2.5.4。更新内容：优化了一些代码，以及删除了"删除进入直播间提示"功能</li>
</ul>
