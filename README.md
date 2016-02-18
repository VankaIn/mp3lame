# mp3lame
在android中，录音生成都是wav格式。

而mp3lame可以帮我们把wav转成mp3格式。

而网上的mp3lame.so都是基于32位，所以在64位上跑就会报错：

java.lang.UnsatisfiedLinkError:xxxxxxxxxxxxxxxxxxxxx  couldn't find "libmp3lame.so" 的问题。

以上是mp3lame官网下载的源码重新编译成兼容对应CPU架构的mp3lame.so库。

利用上面so库能解决上面报的错误
