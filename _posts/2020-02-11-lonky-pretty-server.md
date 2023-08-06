---
layout: default 
title: cuplayer
---

<head>
<style> 
.video-container { position: relative; padding-bottom: 56.25%; padding-top: 30px; height: 0} 
.video-container iframe { position: absolute; top:0; right: 0; width: 100%; height: 100%; float:right} 
</style>
</head>


<div id="ace-content" class="ace-container-shift">
<div class="ace-container"> <div id="ace-nav-wrap" class="hidden-sm hidden-xs">
<div class="ace-nav-cont">
<div id="ace-nav-scroll">
<nav id="ace-nav" class="ace-nav">
</nav>
</div>

<div id="ace-nav-tools" class="hidden">
<span class="ace-icon ace-icon-dots-three-horizontal"></span>

<button id="ace-nav-arrow" class="clear-btn">
<span class="ace-icon ace-icon-chevron-thin-down"></span>
</button>
</div>
</div>

<!-- <div class="ace-nav-btm"></div> -->
</div><!-- .ace-nav-wrap -->
<h2>个人项目</h2>
<div id="player"></div>
<script src='//player.polyv.net/script/player.js'></script>
<div id='plv_dc5e139894ab4cafe10fbbaaa670aa83_d'></div>
<script>
var player = polyvPlayer({
          'wrap':'#plv_dc5e139894ab4cafe10fbbaaa670aa83_d',
            'width':'600',
              'height':'339',
              'muted':'true',
                'vid': 'dc5e139894ab4cafe10fbbaaa670aa83_d',
                  'playsafe': '' // 播放加密视频的凭证, 取值参考文档: https://help.polyv.net/index.html#/vod/api/playsafe/token/create_token 
                  });
player.volume(0);
</script>
视频篇幅有所删减

<h2>GIF</h2>

<a href="https://zlonqi.github.io/2021/02/22/note/"><img src="/styles/img/video3.png" alt=""></a>

<h2>备用源</h2>
<a href="https://zlonqi.github.io/2020/02/11/backup_source/"><img src="/styles/img/video1.png" alt=""><img src="/styles/img/video2.png" alt=""><img src="/styles/img/video3.png" alt=""></a>

<h2>wechat</h2>
<img src="/styles/img/wechart.png" alt="扫一扫+微信">

<!--<video id="video" controls="" preload="none">
    <source id="mp4" src="../../../../../zlonqi/styles/img/t.mp4" type="video/mp4">
</video> -->

</div><!-- .ace-container -->
</div><!-- #ace-content -->

