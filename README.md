### 一、下载依赖包
```
npm install
```
### 二、打包
```
gulp
```

### 三、更新日志
#### 1.11
1. 视频比例调整(index.scss、cheer_1.scss、cheer.scss、uploadVideo.scss、learnPark.scss)
2. 报名信息页面搜索修改(enroll.js)
3. 视频播放按钮错位调整（index.html、index.scss、index.js、uploadVideo_1.html、uploadVideo_2.html、uploadVideo.js、uploadVideo.scss、cheer.html、cheer.scss、cheer.js、cheer_1.html、cheer_1.scss、cheer_1.js、learnPark.html、learnPark.scss、learnPark.js、common.js、cheerGuide.js）
4. uploadVideo_2.html 页面添加初始化判断是否上传，及上传后转变成确认提交状态（uploadVideo_2.html、\static\images\uploadVideo\header3.png）


#### 各个html对应页面：
##### index.html --->  首页
##### rule.html ---> 活动规则(弹窗，需要在页面按钮中调用)
##### attention.html ---> 点击报名-引导关注服务号
##### uploadVideo_1.html ---> 上传视频-选题
##### uploadVideo_2.html --->  点击上传视频 
##### cheer.html ---> 参赛者视角-好友助威
##### cheer_1.html ---> 好友助威
##### cheerGuide.html ---> 新手引导-好友助威(弹窗，需要在前两个页面调用)
##### cheerRule.html ---> 助威规则(从cheer.html页面点开)
##### learnPark.html ---> 学习乐园
##### ichmap.html ---> 非遗小站地图
