``**Python 练习册，每天一个小程序**
    ——(windows平台 Python3.5版本)

部分习题原始出处：https://github.com/Yixiaohan/show-me-the-code

按顺序提交自己的代码

**第 0000 题**：将你的 QQ 头像（或者微博头像）右上角加上红色的数字，类似于微信未读信息数量那种提示效果。

**第 0001 题**：将一组32\*32大小的图标批量缩小成16\*16大小的图标。

**第 0002 题**：随机生成 200 个激活码（或者优惠券）。

**第 0003 题**：随机生成 200 个激活码，并保存到MySQL关系型数据库。

**第 0004 题**：随机生成 200 个激活码，并保存到Redis非关系型数据库。

**第 0005 题**：任一个英文的纯文本文件，统计其中的单词出现的个数。

**第 0006 题**：你有一个目录，放了你一个月的日记，都是 txt，为了避免分词的问题，假设内容都是英文，请统计出你认为每篇日记最重要的词。

**第 0007 题**：有个目录，里面是你自己写过的程序，统计一下你写过多少行代码。包括空行和注释，但是要分别列出来。

**第 0008 题**： 一个HTML文件，找出里面的正文。

**第 0009 题**： 一个HTML文件，找出里面的链接。

**第 0010 题：** 使用 Python 生成类似于下图中的 **字母验证码图片**

![字母验证码](http://i.imgur.com/aVhbegV.jpg)

**第 0011 题：** 敏感词文本文件 filtered_words.txt，里面的内容为以下内容，当用户输入敏感词语时，则打印出 Freedom，否则打印出 Human Rights。

```javascript
    北京
    程序员
    公务员
    领导
    牛比
    牛逼
    你娘
    你妈
    love
    sex
    jiangge
```

**第 0012 题：** 敏感词文本文件 filtered_words.txt，里面的内容 和 0011题一样，当用户输入敏感词语，则用 星号 `*` 替换，例如当用户输入「北京是个好城市」，则变成「`**`是个好城市」。

**第 0013 题：** 用 Python 写一个爬图片的程序，爬 [这个链接里的日本妹子图片 :-)](http://tieba.baidu.com/p/2166231880)

**第 0014 题：** 纯文本文件 student.txt为学生信息, 里面的内容（包括花括号）如下所示：

```javascript
    {
        "1":["张三",150,120,100],
        "2":["李四",90,99,95],
        "3":["王五",60,66,68]
    }
```

请将上述内容写到 student.xls 文件中，如下图所示：

![student.xls](http://i.imgur.com/nPDlpme.jpg)

- [阅读资料](http://www.cnblogs.com/skynet/archive/2013/05/06/3063245.html) 腾讯游戏开发 XML 和 Excel 内容相互转换

**第 0015 题：** 纯文本文件 city.txt为城市信息, 里面的内容（包括花括号）如下所示：

```javascript
    {
        "1" : "上海",
        "2" : "北京",
        "3" : "成都"
    }
```

请将上述内容写到 city.xls 文件中，如下图所示：

![city.xls](http://i.imgur.com/rOHbUzg.png)

**第 0016 题：** 纯文本文件 numbers.txt, 里面的内容（包括方括号）如下所示：

```javascript
    [
        [1, 82, 65535],
        [20, 90, 13],
        [26, 809, 1024]
    ]
```

请将上述内容写到 numbers.xls 文件中，如下图所示：

![numbers.xls](http://i.imgur.com/iuz0Pbv.png)

**第 0017 题：** 将 第 0014 题中的 student.xls 文件中的内容写到 student.xml 文件中，如下所示：

```javascript
    <?xml version="1.0" encoding="UTF-8"?>
    <root>
    <students>
    <!--
    	学生信息表
    	"id" : [名字, 数学, 语文, 英文]
    -->
    {
        "1" : ["张三", 150, 120, 100],
        "2" : ["李四", 90, 99, 95],
        "3" : ["王五", 60, 66, 68]
    }
    </students>
    </root>
```

**第 0018 题：** 将 第 0015 题中的 city.xls 文件中的内容写到 city.xml 文件中，如下所示：

```javascript
    <?xmlversion="1.0" encoding="UTF-8"?>
    <root>
    <citys>
    <!-- 城市信息 -->
    {
        "1" : "上海",
        "2" : "北京",
        "3" : "成都"
    }
    </citys>
    </root>
```

**第 0019 题：** 将 第 0016 题中的 numbers.xls 文件中的内容写到 numbers.xml 文件中，如下所示：

```javascript
    <?xml version="1.0" encoding="UTF-8"?>
    <root>
    <numbers>
    <!--
    	数字信息
    -->
    [
        [1, 82, 65535],
        [20, 90, 13],
        [26, 809, 1024]
    ]
    </numbers>
    </root>
```

**第 0020 题：** 使用 Python 的 Web 框架，做一个 Web 版本 留言簿 应用。

[阅读资料：Python 有哪些 Web 框架](http://v2ex.com/t/151643#reply53)

- ![留言簿参考](http://i.imgur.com/VIyCZ0i.jpg)

**第 0021 题：** most-wanted-letter。

给你一个其中包含不同的英文字母和标点符号的文本，你要找到其中出现最多的字母，返回的字母必须是小写形式，
当检查最想要的字母时，不区分大小写，所以在你的搜索中 "A" == "a"。 请确保你不计算标点符号，数字和空格，只计算字母。
如果你找到 两个或两个以上的具有相同的频率的字母， 返回那个先出现在字母表中的字母。 例如 -- “one”包含“o”，“n”，“e”每个字母一次，因此我们选择“e”。

**第 0022 题：** 提取win10锁屏壁纸。

win10壁纸一般存放在`C:\Users\[用户名]\AppData\Local\Packages\Microsoft.Windows.ContentDeliveryManager_cw5n1h2txyewy\LocalState\Assets`中，可以通过python批量进行提取。