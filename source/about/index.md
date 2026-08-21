---
title: 关于我
layout: about

---

# 关于我...

嗯……<span id="greeting">你好</span>？我猜。

很高兴你能来到这里，这里是 虚构观测 主创团队成员 VOJHX 的博客

嗯，总之，欢迎你来到这里，希望通过这里，你能更好的了解 **我** 。

如果你想，可以来参观一下 [我们的 YouTube](https://www.youtube.com/@Virtual-Observer) 和 [我们的 Github](https://github.com/VOJHX)

## 为什么要关闭评论区？

烦

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

