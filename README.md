# btulz.nodejs
这是Node.js环境下的开发工具集。

## 安装说明 | install
* nodejs环境下：
~~~
npm install -g btulz
~~~

## 使用说明 | instructions
### types-ui5 生成OpenUI5库文件
~~~
btulz types-ui5 v1.61.2
~~~
* 参数1（data）：可以是说明文件目录或文件；也可是版本号，版本号时自动从网站下载说明文件。
* 参数2（out）：生成的库文件输出目录，默认为当前目录。

### wsdl-to-ts 分析wsdl生成typescript库
~~~
btulz wsdl-to-ts ./sample.wsdl ./out "org.colorcoding" "int=number;decimal=number;"
~~~
* 参数1（wsdl）：wsdl文件。
* 参数2（out）：生成的库文件输出目录，默认为当前目录。
* 参数3（namespace）：额外命名空间，例如：org.colorcoding。
* 参数4（typedefs）：额外的类型定义，例如：int=number;decimal=number;。


## 鸣谢 | thanks
[牛加人等于朱](http://baike.baidu.com/view/1769.htm "NiurenZhu")<br>
[Color-Coding](http://colorcoding.org/ "咔啦工作室")<br>
