# 特点

开源的多站点跨平台阅读器来啦！

支持多来源的自定义阅读器与播放器。

用flutter开发，全平台支持，支持windows，安卓，ios，macos，linux，tv，6个平台。

ps: 所有内容来自互联网，app本身只是工具，不提供内容。

欢迎意见或建议，喜欢不妨点个star。

### 亦搜

多种来源，有发现，可搜索

### 亦看

看文字，看小说，看图片，看壁纸，看漫画，看视频

### 亦闻

听故事，听有声，听音乐，听英语

### 亦你所想，亦你所能

更多功能由君发挥，待君开发。

# 功能列表

- 平台
  - [x] 安卓
  - [x] tv（大白版，感谢大白）
  - [x] ios（需要自签）
  - [x] windows（需安装vc++运行库）
  - [x] Linux
  - [x] Macos
- 搜索
  - [x] 按类型或全部搜索
  - [x] 并发数调整
  - [x] 精确搜索
  - [x] 搜索词历史记录
- 发现
  - [x] 二级发现列表
  - [x] 多种样式，优化视频、文字、图片显示
  - [x] 小分类可搜索、收缩
- 视频播放
  - [x] 音量、亮度手势
  - [x] 左右滑动调整进度
  - [x] 进度条拖拽
  - [x] 友好的提示
  - [x] 投屏：DLNA
  - [ ] 直播优化
  - [x] 后台播放
- 文字浏览
  - [x] 图文混排
  - [x] 自定义边距、行距、段距、缩进调整
  - [x] 亮度调整
  - [x] 屏幕常亮开关
  - [x] 预加载
  - [x] 使用缓存加速正文加载
  - [x] 章节快速拖拽
- 图片查看
  - [x] 方向可选上到下、左到右、右到左
  - [x] 显示章节、系统信息
  - [x] 缩放
  - [x] 单独查看
  - [x] 进度条拖拽
  - [x] 图片保存
- 音频播放
  - [x] 单曲循环
  - [x] 歌单循环
  - [x] 搜索结果循环
  - [x] 后台播放
- 规则
  - [x] 网络导入
  - [x] 剪贴板导入导出
  - [x] 分享
  - [x] 规则压缩编码
  - [x] 规则调试
  - [x] 规则排序
- 其他
  - [x] 首次进入显示版本信息
  - [ ] 启动时检查章节更新
  - [ ] 换源

# 编译指南

不同平台有些插件不兼容，准备了多个依赖文件列表，必要时可替换yaml。

linux运行需要额外安装libsqlite3-dev，macos和linux编译需要dev分支，windows需要master分支。

源码去除规则解析部分，但不影响编译和运行，效果相同，仅仅固定了数据内容，可通过`api/api_manager.dart`修改.

# 规则获取

规则仓库 [eso_source](https://github.com/mabDc/eso_source)

`https://github.com/mabDc/eso_source`

规则百科 [wiki](https://github.com/mabDc/eso_source/wiki)

`https://github.com/mabDc/eso_source/wiki`

# 更新日志

见文件 [CHANGELOG](CHANGELOG.md)

# 致谢

感谢大白和大古为项目提交的代码，具体看 [CHANGELOG](CHANGELOG.md)

大白 [yangyxd](https://github.com/yangyxd) 界面等

大古 [DaguDuiyuan](https://github.com/DaguDuiyuan) ios和macos平台代码等

ekibun [ekibun](https://github.com/ekibun) 帮助编写桌面平台c++代码等

# LICENSE

[GPL_v3](LICENSE)

# 一些图片

首先是视频，支持DLNA投屏，有音量、亮度、进度调节的手势控制。

![视频](img/shipin1.jpg)

![视频](img/shipin3.jpg)

![视频](img/shipin2.jpg)

![视频](img/shipin4.jpg)

还有图片、壁纸、阅读等功能：

![新漫画](img/xinmanhua1.jpg)

![新漫画](img/xinmanhua3.jpg)

![新漫画](img/xinmanhua2.jpg)

![壁纸](img/bizhi1.jpg)

![北邮](img/beiyou1.jpg)

![知乎日报](img/zhihuribao1.jpg)

![知乎日报](img/zhihuribao2.jpg)