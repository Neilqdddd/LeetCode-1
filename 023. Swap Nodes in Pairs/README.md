又是我擅长的链表题，诀窍就是画图，在纸上用铅笔连来连去，就很容易发现断在哪。

这道题的关键在于，**交换两个节点，不仅仅是这两个节点之间的事情，还是这两个节点前后节点，一共为4个节点的事情。**

-----

就好比结婚，不是两个人的事，而是两个家庭的事一样。

-----

抓住这个关键就好解决了，我先开始倒腾半天，都觉得费劲，就是因为**我的思维是顺其自然的往后看的**，但这与上面的关键矛盾：
第一个节点没有前节点，又要参与交换，可怎么办呐？就像你结婚，对方没父母，婚礼咋整啊？ 聪明，找个代理人即可。

这道题的第二个关键，就是你找没找这个代理人，我找到了，在 head 前面加上了一个 newHead，问题解决。
