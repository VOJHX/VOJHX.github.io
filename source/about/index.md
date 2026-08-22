---
title: 关于我
layout: about

---

# 关于我...

嗯……<span id="greeting">你好</span>？我猜。

很高兴你能来到这里，这里是 虚构观测 主创团队成员 VOJHX 的博客

嗯，总之，欢迎你来到这里，希望通过这里，你能更好的了解 **我** 。

如果你想，可以来参观一下 [我们的 YouTube](https://www.youtube.com/@Virtual-Observer) 和 [我们的 Github](https://github.com/VOJHX)

# 碎碎念

嗯……就我在编写这篇页面的时间来说，可能还要对我自己说一声 晚上好 吧。

嗯，果然晚上的时间才是最棒的，也只有晚上能这样安静，就像是整个世界都安静下来了一样。

不过，世界安静下来与否和我没什么关系，我只是想要我自己的世界更安静而已。

虽然是这么说，但是在我的小小世界中，弄出噪音的好像都是我自己呢……无论是自己房间里面摆满的奇奇怪怪小乐器，还是时不时会说起来奇怪的话的我自己。

嗯，这是我，我是 VOJHX ，没问题。

# 名字？

VOJHX ，这个名字倒是没什么特别的，只是随随便便的五个字母而已，非要说的话，本来想要四个字母，但是 GitHub 上似乎都被抢注得差不多了，所以，脸滚键盘得到了这样的一个用户名，然后通过了 GitHub 的账号验证，就是这么简单。

# 博客为什么不开放评论区？

**没用且没有必要。**

我讨厌那些 无论什么话题，即使不是自己了解的领域，却还要发表自己的评论的人，我一般管这种巨婴行为叫作抬杠。再者说，这里也只是我发表一些我的奇怪想法的地方，我也不在乎、更不想听别人对我的想法的意见。

这也是我日常的态度，在网上遇见这种习惯性抬杠的“人”，除非这人能杠出新高度，杠出新角度，要不然我是直接 black list +1 的。这种杠精少不了，但是，至少能确定的一点是，我的 black list 越大，我的耳根子越清静。

---

嘛，总之，先欢迎你来到这个站点，希望你在这里可以度过愉快的几分钟。

<script>
(function() {
    const now = new Date();
    const hour = now.getHours();
    let greeting = "";

    if (hour >= 5 && hour < 9) {
        greeting = "早上好";
    } else if (hour >= 9 && hour < 12) {
        greeting = "上午好";
    } else if (hour >= 12 && hour < 14) {
        greeting = "中午好";
    } else if (hour >= 14 && hour < 18) {
        greeting = "下午好";
    } else if (hour >= 18 && hour < 23) {
        greeting = "晚上好";
    } else {
        greeting = "深夜好";
    }

    document.getElementById("greeting").innerText = greeting;
})();
</script>

