## 说明

js及css已本地化，根据功能分类，请勿合并

## 更新

- 添加聊天室组件【emb.js】https://noise.zhubai.love/posts/2212598888907571200
- 添加图标引用：https://fontawesome.com
- 添加loading载入效果【loading.css;loading.js]
- 添加随机背景+随机前景【suiji-picture.js】
- 添加主页问候提醒弹窗【时间分类】
- 添加侧边圈形按钮菜单【tb.css;tab.js】
- 更新双击头像终端菜单【引入抖音、tiktok去水印下载命令】
- 引入PWA【service-worker.js】
- 更换切换风格页【home.html】
- 添加广告位图文弹窗，自动轮询播放，点击可关闭，仅在电脑端尺寸下显示【AD.css;AD.js】
- 添加弹入弹出式侧边文字【Text.css;Text.js】
- 更新公共服务页【增加单页播放室、N8N实例、RSSHUB实例】
- 添加手机端向下滑动提示
- 修改主界面css布局
- 添加RSS信息动态展示,手机端尺寸不显示【rss.css;rss.js】
- 添加隐藏式数字时钟及隐藏式底部页脚

## 清除PWA缓存

添加了两个缓存方案

1. service-worker.js文件内更换cacheName版本号会自动清除上个版本设置的缓存文件
2. 主页index.html文件内，找到注释<!-- 添加版本号-每次更新要改版本号才会刷新缓存 -->更新下面自己设置缓存的文件的版本号
3. 清除本地浏览器缓存
