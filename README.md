## fast-tools
> 常用自定义node脚本

#### 使用
```
git clone https://github.com/Furion-Prophet/fast-tools.git
yarn install
yarn link
```
yarn link失败时查看下是否权限异常
异常时以管理员身份运行
```
sudo yarn link
```

目前支持命令 \
1.基于tinify封装的压缩图片工具
```
minimg 图片文件或者图片文件夹路径
```
> 可指定文件或文件夹，指定文件夹会对文件夹内所有图片进行压缩并替换

tinify压缩接口每个月免费额度500次，要使用的话自己申请一个账号生成ApiKey，替换掉脚本里面的ApiKeys(==拜托请一定自己申请一个，不要用原文这个，毕竟500次确实只够个人使用==)