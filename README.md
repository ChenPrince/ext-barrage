一个性能较好的，视频弹幕组件(系统)🍻

A video barrage component (system) with good performance 🍻

</br>

<strong>🎈Tip：如果你感兴趣，或者也跃跃欲试，你可以给我点亮一个⭐，这将是最大的鼓励，我将适时开源代码。</strong>


Tip: if you are interested or eager to try, you can light up one for me ⭐， This will be the greatest encouragement. I will open source code in due course.

<center>
<h1> Ext Barrage </h1>
</center>

<img src="./resource/preview.png">

</br>

<div>
    <h2>简介</h2>
    <hr/>

🏹视频弹幕弹幕在绝大部分视频类主题网站中都是必不可少的功能，该项目的目标是实现一个轻量化、高性能、高拓展性、高可玩度的弹幕组件(系统).
        
Video barrage Barrage is an essential function in most video themed websites. The goal of this project is to achieve a barrage component (system) with lightweight, high performance, high scalability and high playability

</br>
        
🎂目前弹幕策略任然没有摆脱主流网站的方案，希望接下来可以找到一个更优解。

At present, the barrage strategy still hasn't got rid of the scheme of mainstream websites. I hope we can find a better solution next.
        
    
</div>

<br/>
<h2>策略</h2>

strategy
<hr/>
🏫当前使用的方案是单轨道内部调节、节点复用、css3动画。每一个弹幕节点将会有三种状态：活跃、沉睡、待销毁。

The current schemes are single track internal adjustment, node reuse and CSS3 animation. Each barrage node will have three states: active, sleeping and to be destroyed.

</br>

<span style="color:#f4f">✨可以将整个系统的节点数，内存占用量控制在一个线性的，可预知的阈值内。

<span style="color:#f4f">The number of nodes and memory usage of the whole system can be controlled within a linear and predictable threshold.

<img src="./resource/strategy-策略1.png">
<br/>
<br/>
<h2>性能</h2>

performance
<hr/>

与bilibili的简单对比，这也许是不严谨的，但是也可以些许体现出，ext-barrage在内存控制上的优点

Compared with BiliBili, this may not be rigorous, but it can also reflect the advantages of ext barrage in memory control

<img src="./resource/performance-性能2.png">
[ext-barrage]

<img src="./resource/bilibili2.png">
[bilibili]


对比视频源:
https://www.bilibili.com/video/BV1Uv4y137ee?spm_id_from=333.851.b_7265636f6d6d656e64.6&vd_source=6fd78a9675ae5b963547ead3169f66ef


<br/>
<h2>不足</h2>
<hr/>

就像需求一样，永远做不完的🙏

Just like the demand, it can never be finished🙏