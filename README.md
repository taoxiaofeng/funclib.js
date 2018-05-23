# funclib.js (凡客杰斯)

### Version
Javascript通用型逻辑函数封装 funclib: V2.0.1

### Quick start
```bash
# Install funclib.js
$ npm install funclib

# Use funclib
$ node
> var fn = require('funclib');
> console.log(fn.gnid()) // => 8GH9IYO60MXQ
```

### Contribute
```bash
# Download funclib repo
$ git clone https://github.com/CN-Tower/funclib.js.git

# Install dependency
$ npm install

# Start
$ npm start

# Build
$ npm run build
```

### Methods

- fn.version           返回当前函数库版本
- fn.tools             NodeJs工具包
- fn.progress          控件台进度条工具
- fn.bootstrapTable    渲染Bootstrap表格
- fn.time              返回当前时间字符串
- fn.gnid              返回指定长度(最小6位)的随机ID
- fn.array             返回指定长度和默认值的数组
- fn.random            返回指定范围的随机数
- fn.objLen            获取对象自有属性的个数
- fn.deepCopy          深拷贝数组或对象
- fn.interval          循环定时器
- fn.timeout           延时定时器
- fn.sortData          对象数组根据字段排序
- fn.currency          格式化显示货币
- fn.cutString         裁切字符串到指定长度
- fn.overlay           给对象赋值，可指定字段
- fn.getPattern        获取一个通用的正则表达式
- fn.matchPattern      与一个或几个通用正则匹配
- fn.fullScreen        全屏显示一个HTML元素
- fn.exitFullScreen    退出全屏显示
- fn.checkIsFullScreen 检测是否处理全屏状态
- $.pollingElement     jQuery获取异步出现的元素
- $.noAutoComplete     jQuery禁止input密码自动填充
- $ele.findCousin      jQuery获取元素表亲
