# 年会抽奖程序
fork自[https://github.com/fouber/lottery](https://github.com/fouber/lottery)   

[抽奖demo](https://ketra21.github.io/lottery/)

## 使用办法：
1. 建一个网站

    首先得有个网站，如果没有，可以使用Github.io博客，建站方法可参考[这篇文章](https://github.com/qiubaiying/qiubaiying.github.io/wiki/%E5%8D%9A%E5%AE%A2%E6%90%AD%E5%BB%BA%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B)，如果建站只是为了抽奖，能成功打开`你的Github账号名.github.io`，五分钟就搞定~即可进入下一步；

2. 增加一个页面

    即在`你的Github账号名.github.io`网站中增加一个页面，得到`你的Github账号名.github.io/lottery`。具体方法参考[这篇文章](http://chitanda.me/2015/11/03/multiple-git-pages-in-one-github-account/)

## 抽奖流程：

1. 选择当次要抽奖的人数（30、10、5、2、1）
2. 点击『开始』按钮，进入抽奖状态（这个过程仍可修改抽奖人数）
3. 点击『停！』按钮，生成抽奖结果
4. 点击任意人数按钮，可以回到闲置状态，已中奖的用户标记为黄色，不会二次命中
5. 抽奖完毕，点击网页右上方的`中奖名单`即可查看。

PS：滚动鼠标滚轮，可以放大或缩小球体

抽奖过程
![image.png](https://github.com/ketra21/lottery/blob/master/img/demo-lottery.png)

抽奖结果
![image.png](https://github.com/ketra21/lottery/blob/master/img/demo-result.png)


## 个性化设置

1. **修改号码和名单**  

    在'js/member.js'文件内，可修改编号和名称。

2. **修改抽奖人数和默认值列表**  
 
    默认抽奖人数为【30，10，5，2，1】，默认值为30，可以在index.html中修改

```
        new Vue({
            el: '#tools',
            data: {
                selected: 30,
                running: false,
                btns: [
                    30, 10, 5, 2, 1
                ]
            },
```

3. **修改奖项**

    待续

4. 教程很详细啦。如果你懒得自己弄，请我吃个雪糕，我可以帮你。


这个[github地址](https://github.com/moshang-xc/lottery)  看着更炫酷，功能更多，但我还没试过。
