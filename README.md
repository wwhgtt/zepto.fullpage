# zepto.fullpage 

[![release](https://img.shields.io/badge/release-v0.3.1-orange.svg)](https://github.com/yanhaijing/zepto.fullpage/releases) [![issues](https://img.shields.io/github/issues/yanhaijing/zepto.fullpage.svg)](https://github.com/yanhaijing/zepto.fullpage/issues) [![forks](https://img.shields.io/github/forks/yanhaijing/zepto.fullpage.svg)](https://github.com/yanhaijing/zepto.fullpage/network) [![stars](https://img.shields.io/github/stars/yanhaijing/zepto.fullpage.svg)](https://github.com/yanhaijing/zepto.fullpage/stargazers) [![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/yanhaijing/zepto.fullpage/blob/master/LICENSE)

专注于移动端的fullPage.js，依赖Zepto。

## 功能概述
可实现移动端的单页滚动效果，可自定义参数，提供回调接口，和公开接口。

## 兼容性

- Ios4+
- Andriod2.3+（未全部覆盖）

## 快速上手
### HTML

	<div class="wp">
        <div class="wp-inner">
            <div class="page page1">1</div>
            <div class="page page2">2</div>
            <div class="page page3">3</div>
            <div class="page page4">4</div>
        </div>
    </div>

### CSS
父容器需是固定高度，并且溢出为隐藏，fullpage会使用父元素的宽度和高度。

	.wp{
	    overflow: hidden;            
	}

## js
一行代码即可完成，如此简单：

	$('.wp-inner').fullpage();

**注意：是在.wp-inner上调用的。**

更多例子，请移步[这里](demo)。

## 文档

[API](doc/api.md)

## 贡献指南

如果你想为zepto.fullpage贡献代码，请采用fork + pull request 方式，并在发起pr前先将master上超前的代码rebase到自己的分支上。

### 发布Bower
    
    $ bower register zepto.fullpage git://github.com/yanhaijing/zepto.fullpage.git


## 相关链接
- [fullPage.js](https://github.com/alvarotrigo/fullPage.js)
- [onepage-scroll](https://github.com/peachananr/onepage-scroll)
- [zepto-onepage-scroll](https://github.com/peachananr/zepto-onepage-scroll)
- [parallax.js](https://github.com/hahnzhu/parallax.js)
- [H5FullscreenPage](https://github.com/lvming6816077/H5FullscreenPage)
