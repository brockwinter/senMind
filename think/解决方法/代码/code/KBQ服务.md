KBQ我理了下写的过程, 首先看KBQ服务
E:\workspace\svn\standard\cpp\include\cyg\pub\commcyg_kbq  KBQ服务接口
E:\workspace\svn\standard\cpp\src\platform\business\dw\fw\baseFramework\2124cyg_kbq KBQ服务接口代码实现

这里的代码, 了解清楚原来的代码数据从哪儿来, 怎么来, 经过了什么样的处理, 要到哪儿去, 用到了哪些库, 这些库都是咋起作用的.
猜想: KBQ服务和KBQ配置是不是两套东西啊, KBQ配置界面并没有调用KBQ服务的东西, 会不会是KBQ配置只往数据库里写东西, KBQ服务从数据库里读东西, 并进行服务的? 总之这可能要分开来看.

那么KBQ服务可能的作用就是起来一个东西, 所以看上面那里的代码, 我就得看清楚跑起来了啥代码.

那么KBQ界面, 我就得整个读完一遍, 了解清楚原来的代码数据从哪儿来, 怎么来, 经过了什么样的处理, 要到哪儿去, 用到了哪些库, 这些库都是咋起作用的. 先搞KBQ服务吧