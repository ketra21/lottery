# 年会抽奖程序
fork自[https://github.com/fouber/lottery](https://github.com/fouber/lottery)    
这个[github地址](https://github.com/moshang-xc/lottery)  
[demo](https://ketra21.github.io/lottery/)



## 抽奖流程：

1. 选择当次要抽奖的人数（30、10、5、2、1）
2. 点击『开始』按钮，进入抽奖状态（这个过程仍可修改抽奖人数）
3. 点击『停！』按钮，生成抽奖结果
4. 点击任意人数按钮，可以回到闲置状态，已中奖的用户标记为黄色，不会二次命中

PS：滚动鼠标滚轮，可以放大或缩小球体

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
