# ThunderParser
迅雷下载地址解析库

该库当前支持解析迅雷、QQ旋风、快车的下载链接,主要是为了解决Linux下下载上述链接的问题。再配合其他的下载库,可以方便的下载文件。  
当前版本为0.14.1,使用方法如下:

```
from ThunderParser import parser
url = "下载的链接地址"
print(parser(url))
```

我们只需要将迅雷、QQ旋风、快车的下载链接传递到parser方法中,即可得到真实的下载地址了。