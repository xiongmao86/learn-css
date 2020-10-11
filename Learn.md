
- 祖父级的align-items会对当前的元素有影响吗？

    > 会，看"align-items in grandfather.html"

    > 实际上align-item通过影响父元素而对当前元素做出影响，我由
    于受到stretch词义影响，以为拉伸父元素会导致当前元素也被拉
    伸，以为svg的height会被改变，实际上拉伸父元素仅仅是导致当前
    元素往上移了，这个似乎是height计算的问题。

    > 所以实际上flex盒子模型仅仅在两层元素上七座用。