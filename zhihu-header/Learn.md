
- 祖父级的`align-items`会对当前的元素有影响吗？

    > 会，看"align-items in grandfather.html"

    > 实际上align-item通过影响父元素而对当前元素做出影响，我由
    于受到stretch词义影响，以为拉伸父元素会导致当前元素也被拉
    伸，以为svg的height会被改变，实际上拉伸父元素仅仅是导致当前
    元素往上移了，这个似乎是height计算的问题。

    > 所以实际上flex盒子模型仅仅在两层元素上七座用。

- 设置了伪元素::after为什么dev-tools的elements里不显示？
    > 需要在css里加上`content: ""`.

- 为什么屏幕上不显示？

    > 需要设置left和right以便将框扩大，否则框的宽度是0，就不显示。

    > 还要设置好relative以便定位absolute元素。

- 为什么首页、发现、等你来答左右没有padding？
    > padding的格式是`padding: 上下 左右`，把a元素的padding误解成
    设左右了。

- [ ] 仅仅设置`display: flex`会造成什么影响？

- 为什么img不显示？
    > 把`src`写成`href`。