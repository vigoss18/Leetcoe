几乎从来没有用链表写过题，第一次写完之后对着无尽的CE一筹莫展。

看了别人的题解了解了一下语法，就好写了。其实题目也很简单，只要让你实现简单的链表加法。

第一次写完的时候发现答案结尾总是多一个0的结点，查看代码后发现是因为把构造next结点的代码写在了循环的最后，于是把构造结点的代码扔到循环最前面……然后返回开始结点的后一个结点，就AC了。
