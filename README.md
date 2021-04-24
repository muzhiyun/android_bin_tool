# android_bin_tool
ARM/Android tool statically compiled binary file backup

部分开源项目提供Source code并不提供二进制执行程序，所以偶尔会收集或者自己静态交叉编译一些终端小工具用于Android平台debug，直到有一天3281U盘掉固件了~~ 所以就有了这个project

本意备份应付临时急用保证可用性，尽可能然而并不保证为最新版本。

- tinyalsa

     Source：[https://github.com/tinyalsa/tinyalsa](https://github.com/tinyalsa/tinyalsa)

- v4l2-ctl

    Source：[https://github.com/9crk/v4l2-ctl](https://github.com/9crk/v4l2-ctl)

- tinybox

    Source：[http://landley.net/toybox/bin/](http://landley.net/toybox/bin/)

- busybox

    Source：[https://busybox.net/downloads/binaries/1.31.0-defconfig-multiarch-musl/](https://busybox.net/downloads/binaries/1.31.0-defconfig-multiarch-musl/)

- ethtool

     Source：[https://github.com/giraffesnn/ethtool](https://github.com/giraffesnn/ethtool)

- ffmpeg

    Source：[https://johnvansickle.com/ffmpeg/](https://johnvansickle.com/ffmpeg/)

- v4l2loopback

    Source：[https://github.com/umlaeute/v4l2loopback](https://github.com/umlaeute/v4l2loopback)
    
    由于kernel module存在version magic，故无法提供v4l2loopback.ko，该子文件下提供实际为v4l2loopback的examples文件夹中测试程序的静态编译版本