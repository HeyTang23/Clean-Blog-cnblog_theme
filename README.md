## 食用方法

1. 首先你得有个[博客](http://www.cnblogs.com/)

2. 打开 [博客后台管理](https://i.cnblogs.com/Configure.aspx)

3. 申请js权限

4. 在博客皮肤选项卡中将博客皮肤设置为： [BlueSky](http://www.cnblogs.com/SkinUser.aspx?SkinName=BlueSky)

5. 将 [页面定制.css](https://github.com/Summertime-Wu/make_cnblogs_better/blob/master/%E9%A1%B5%E9%9D%A2%E5%AE%9A%E5%88%B6.css) 复制到 `页面定制CSS代码` 代码框内

6. 将 [页首.html](https://github.com/Summertime-Wu/make_cnblogs_better/blob/master/%E9%A1%B5%E9%A6%96.html) 复制到 `页首Html代码` 代码框内

7. 将 [页尾.html](https://github.com/Summertime-Wu/make_cnblogs_better/blob/master/%E9%A1%B5%E5%B0%BE.html) 复制到 `页脚Html代码` 代码框内

8. 根据自身情况修改页尾.html中的js

```javasript
<script type="text/javascript">
    document.getElementById("mainContent").id = 'content';
    document.getElementById("content").setAttribute("class", "container");
    var nickName = null;
    var subheading = "世间每一次相遇，都是久别重逢";
    var contact = "https://msg.cnblogs.com/send/D-arling";
    var set_up = "https://i.cnblogs.com/settings";
    var about = "https://www.cnblogs.com/D-arling/p/14711119.html";
    document.getElementById("about").setAttribute("href", about);
    document.getElementById("contact").setAttribute("href", contact);
    document.getElementById("set_up").setAttribute("href", set_up);
</script>
```

8. 保存，即可食用

## 博客示例

------------------------>>> [只是条咸鱼罢了](https://www.cnblogs.com/D-arling/)


## 鸣谢

[夏日浅笑、](https://www.cnblogs.com/summertime-wu)
