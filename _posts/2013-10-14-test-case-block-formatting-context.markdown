---
layout: test-case
title:  "the test cases for block formatting context"
date:   2013-10-14 11:04:15 +0800
tags: BFC
categories: test-case
---
<style>
  
</style>
<div style="background-color: red;"><div style="float: left;">我浮动了，我的父元素没有浮动，我父元素塌缩了</div></div>
<div style="float: left; background-color: red; clear:both;"><div style="float: left;">我浮动了，我的父元素也浮动了，我父元素没有塌缩</div></div>



