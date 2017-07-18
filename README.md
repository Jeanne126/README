# UdaciFeeds

## 项目预览

编写基于 web 且拥有完整测试用例的读取 rss 源的应用。

## 项目位置
打开`index.html` 和 `./jasmine/spec/feedreader.js` 对应用进行测试。

## 项目思路

查看项目的 HTMl (./index.html), CSS (./css/style.css) 和 JavaScript (./js/app.js) 文件来对项目的工作原理有一个基本的了解。<br>
查看 Jasmine spec 文件 ./jasmine/spec/feedreader.js 然后翻阅阅读 Jasmine 文档。<br>
编辑 ./js/app.js 里面的 allFeeds 变量使给出的测试通不过，然后观察Jasmine是怎么展示应用的错误信息的。<br>
将 allFeeds 变量返回给一个短暂的状态。（待修改）<br>
编写一个测试遍历 allFeeds 对象里面的所有的源来保证有链接字段而且链接不是空的。<br>
编写一个测试遍历 allFeeds 对象里面的所有的源来保证有名字字段而且不是空的。<br>
写一个叫做 "The menu" 的测试用例。<br>
写一个测试用例保证菜单元素默认是隐藏的。你需要分析 html 和 css 来搞清楚我们是怎么实现隐藏/展示菜单元素的。<br>
写一个测试用例保证当菜单图标被点击的时候菜单会切换可见状态。这个测试应该包含两个 expectation ： 党点击图标的时候菜单是否显示，再次点击的时候是否隐藏。<br>
写一个叫做 "Initial Entries" 的测试用例。<br>
写一个测试保证 loadFeed 函数被调用而且工作正常，即在 .feed 容器元素里面至少有一个 .entry 的元素。<br>
写一个叫做 "New Feed Selection" 的测试用例。<br>
写一个测试保证当用 loadFeed 函数加载一个新源的时候内容会真的改变。<br>
每个测试都不应该依赖别的测试的结果。<br>
回调函数应该用来保证在测试运行之前源已经被加载。<br>
实现未定义变量和数组越界的错误处理。<br>
当完成所有任务的时候，所有的测试也应该通过。<br>

