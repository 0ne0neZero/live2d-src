# live2d-src
一个用live2d运动的小姐姐

访问： https://asvue.github.io/live2d-src/src/index.html

# 启动
随便打开个web服务器把文件夹丢上去,然后访问index.html就行.如nginx

#关于模型
原本官方自带的模型丑的要死.我是自己去药水制造师这个游戏里抓取的.太多的衣服了,只弄了大概23套.2个人物的模型
用到的工具 AssetBundleExtractor.exe  Unity Studio.exe




目录结构说明
------------

```bash
.
├── README.md
├── lib                     # 一个大佬改版后的live2d文件.有兴趣可以自己看
├── pio                     # 资源文件,包含模型 动作 和配置
├── 1.css                   #顾名思义 样式文件
├── 1.js                    # 顾名思义 js文件.主要是小姐姐头上的框框
├── index.html              # 入口文件 启动点这个就行
├── LAppDefine.js           # live2d官方源文件.没引用
├── LAppLive2DManager.js    # live2d官方源文件.没引用
├── LAppModel.js            # live2d官方源文件.没引用
├── live2d.js               #main.js编译后的文件,必不可缺     
├── main.js                 # live2d官方源文件.没引用.就是让你们看看关系
├── PlatformManager.js      # live2d官方源文件.没引用
└── webglcontext.js         # live2d官方源文件.没引用

```