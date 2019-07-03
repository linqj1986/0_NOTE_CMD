# 0_NOTE_CMD

#================================================

##ios
```
1.砸壳
su
chmod 777 dump.py
cd /opt/dump/frida-ios-dump
./dump.py QQ

2.导出头文件
/opt/MonkeyDev/bin/class-dump -s -S -H --arch arm64 /opt/frida-ios-dump/output/Payload/QQ.app -o /opt/frida-ios-dump/output/header/qq

3.查看进程
ps -A | grep QQ

4.包操作
dpkg -l
mv /bin/sdfsfhjgdjfgasjdfgjasdgjsdf /bin/rm
dpkg --force-all -P com.cyjh.kaolaservice-yzj
dpkg --force-all -P com.cyjh.kaolaservice
dpkg --force-all -P com.touchsprite.ios.arm64.v3
killall -9 SpringBoard

5.签名dylib
ldid -S xxx.dylib

6.打包ipa包
zip -q -r ddy.ipa Payload

7.
```

#================================================

##git

```
1.查看状态
git status
如果路径不对则更换路径
Git checkout 0.0.1

2.提交到本地
git add --a
git commit -m "提交时的备注"

3.提交到远程
git push origin [master|0.0.1]

4.创建分支
Git branch 0.0.1

5.删除目录
Git rm xx/xx -r

6.github操作
a.github上创建项目,复制https://github.com/linqj1986/0_NOTE_CMD.git
b.终端下载目录git clone https://github.com/linqj1986/0_NOTE_CMD.git
c.开始修改
d.git add --a
e.提交git commit -m "提交时的备注"
f.git push -u origin master


7.更新远程到本地
git fetch orgin master
```

#==================================================

##pod
```
1.创建podspec文件
pod spec create JALCommunityPage
pod lib lint

2.添加关联
pod repo add JALCommunityPage https://github.com/linqj1986/JALCommunityPage.git
pod repo lint

3.提交到pod
pod repo push JALCommunityPage JALCommunityPage.podspec
```

