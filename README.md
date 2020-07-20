# wiki-to-thir



## 使用的库

```python
import urllib
import requests
import re
import time
from bs4 import BeautifulSoup
from selenium import webdriver
```

## chromedriver

使用selenium调用chrome浏览器需要使用chromedriver

- 首先需要下载Chromedriver载后得到的是一个chromedriver.exe文件，chromedriver下载地址:
http://npm.taobao.org/mirrors/chromedriver/

- 将chromedriver.exe拷贝到chrome浏览器、python安装根目录的路径下即可，这样就可以使用selenium启动谷歌Chrome浏览器

Tip：使用的chromedriver要和chrome浏览器的版本需要匹配，否则会出现错误。
