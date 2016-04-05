VisionRemoteImageScroller
=====
* VisionRemoteImageScroller provides infinite scroll on a group of remote images which could autoplay with a specified interval. Scrollable horizontally only. Remote images are loaded by [SDWebImage](https://github.com/rs/SDWebImage/ "SDWebImage"), please install it first. Use [VisionLocalImageScroller](https://github.com/VIIIO/VisionLocalImageScroller "VisionLocalImageScroller") instead if you want to load local images.
* 非常实用、可自动播放的图片滑动器（类似幻灯片效果），可在水平方向无限滚动。图片远程加载依赖于[SDWebImage](https://github.com/rs/SDWebImage/ "SDWebImage")，请自行安装。若只需要加载本地图片，请使用同系列控件：[VisionLocalImageScroller](https://github.com/VIIIO/VisionLocalImageScroller "VisionLocalImageScroller")

### Screenshots
None.

### Contents
## Installation 安装

* Just drag `VisionControl` folder into your project
* 将`VisionControl`文件夹拖入你的項目

### 在你需要使用控件的文件中导入头文件:
```objective-c
#import "VisionRemoteImageScroller.h"
```
## Usage 使用方法
```objective-c
    VisionRemoteImageScroller *scroller = [[VisionRemoteImageScroller alloc] 
                                               initWithFrame:CGRectMake(0, 100, 400, 200)
                                               imageArray:@[@"https://imageURL/",
                                                            @"https://imageURL/",
                                                            @"https://imageURL/",
                                                            @"https://imageURL/"]
                                               autoPlay:YES];
    [self.view addSubview:scroller];
```

## Features 特性
* load remote images by HTTP URLs</br>
* support custom placeholder image</br>
* infinite scroll</br>
* support autoplay</br>
* 仅提供图片URL即可完成图片组的加载</br>
* 可自定义占位图片</br>
* 可无限滚动</br>
* 支持自动播放</br>

## Requirements 要求
* [SDWebImage](https://github.com/rs/SDWebImage/ "SDWebImage")

* iOS 6 or later. Requires ARC  ,support iPhone/iPad.
* iOS 6及以上系统可使用. 本控件纯ARC，支持iPhone/iPad横竖屏

## More 更多 

Please create a issue if you have any questions.
Welcome to visit my [Blog](http://blog.viiio.com/ "Vision的博客")

## Licenses
All source code is licensed under the [MIT License](https://github.com/VIIIO/VisionRemoteImageScroller/blob/master/LICENSE "License").

