1. 本文原创于:https://github.com/UoUoio/YiSaiTong,后续有更新也会更新在该地址
2. 本文仅作为闲暇时无聊的研究,因使用本文造成的其他用途,本人不承担任何责任,侵权联系删除
3. 本文不含任何破解,hook等操作
4. 本文是基于windows来进行创建的
5. 解密后文件传输,可能会有文件传输的操作记录,请勿泄密

#### 使用本文前默认您已经知晓并同意上述内容



### 1. 默认卸载码卸载-正常方式

> 默认卸载码为:12345678
>
> 或者:123456
>
> 如果不对就只能找管理员进行正常卸载了

### 2. 强制卸载-非正常方式

(卸载后,文件好像不会自动解密,时间太久远都忘记了),如果仅仅是为了解密文件,就直接去看 [ 3. 文件传输自动解密 ]

> 之前弄得都忘记了,原理就是删除掉他校验你是否可以卸载的程序,然后再进行卸载,这样就不会校验直接就能卸载了
>
> 由于时间久远都忘记了,这里使用一个更暴力的方式 老规矩:执行前自行判断是否有影响,我不承担任何责任
>
> 1. 打开C:\Program Files\EsafeNet 路径(安装路径)
> 2. 删除Cobra DocGuard Client文件夹
> 3. 这时候他会提示你有些文件正在使用无法删除,你只要点击跳过就行,(太多了就选记住选项直接全部在使用的全部跳过)
> 4. 然后再去下载个UninstallToolPortable.exe 软件卸载工具卸载就行了(不一定是这个软件,随便找个软件卸载工具卸载后能清注册表的都行)

### 3. 文件传输自动解密

> 前提: 
>
> 1. 你需要可以正常打开该文件
>
> 步骤:
>
> 1. 找到配置文件 C:\Program Files\EsafeNet\Cobra DocGuard Client\DdeOpenExcelSuffix.ini
> 2. 打开配置文件参照图中示例在需要在策略的每个后缀前增加;符号(删除也行,推荐使用;符号注释的方式)
> 3. 将文件通过微信(网盘也行)传输到手机上(未加密的设备上),用手机看下是否可以打开这个文件
> 4. 手机不能打开的话就重启电脑,然后再重复一下第三步
>
> 
>
> 原理:
>
> 1. 原理很简单,就是什么后缀文件加密,什么后缀的文件不加密,是由管理员进行配置,然后用户更新配置的
>
>    而这个操作就是修改一下你更新下来的配置
>
> 
>
> 后话:
>
> > 不要去管是不是还有那个加密的小锁图标,那个小锁图标就是显示一下的,我记得这个图标是在另外一个配置文件里的,时间太久远想不起来了
> >
> > 总的来说就是你按照这个方式设置就行了别管什么带不带加密锁的图标



<img src="https://github.com/UoUoio/YiSaiTong/blob/main/img/%E8%A7%A3%E5%AF%86%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6.png" alt="image.png" style="zoom: 50%;" />

### 4. 不想有水印

> 1. 右键右下角图标
> 2. 选择地址设置(别管我的为什么和你的不一样)
> 3. 地址里的地址随修改一个,只要和原来的不一样就行
> 4. 然后点击确定,等待提示用户登录失败的弹窗,然后再点击确定,屏幕就没水印了(有些不会弹窗,直接没有水印)

![图像](https://github.com/UoUoio/YiSaiTong/blob/main/img/image.png)

侵删.

