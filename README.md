# MacOSDingTalkRevoke

MacOS 的钉钉防撤回脚本 (蚂蚁钉也是可以用的, 原理是一样的需要自己改了, 蚂蚁钉和钉钉是同一个壳子做的)

## 支持的版本

- 支持 arm64 架构的 7.0.12 版本
- 支持 arm64 架构的 7.6.0 版本
- 支持 arm64 架构的 7.6.10 版本
- 支持 arm64 架构的 7.6.25 版本
- 支持 arm64 架构的 7.6.35 版本
- 支持 arm64 架构的 7.6.45 版本

主要是自用的, 里面的原理很简单, 就是替换 js 的代码, 有兴趣的可以自己看看

## 下载地址

官方下载地址:

- [DingTalk v7.0.12.5](https://dtapp-pub.dingtalk.com/dingtalk-desktop/mac_dmg/Release/M1-Beta/DingTalk_v7.0.12.5_28488321_arm64.dmg)
- [DingTalk v7.6.0](https://dtapp-pub.dingtalk.com/dingtalk-desktop/mac_dmg/Release/M1-Beta/DingTalk_v7.6.0_38510687_universal.dmg)
- [DingTalk v7.6.10](https://dtapp-pub.dingtalk.com/dingtalk-desktop/mac_dmg/Release/M1-Beta/DingTalk_v7.6.10_39731775_universal.dmg)
- [DingTalk v7.6.25](https://dtapp-pub.dingtalk.com/dingtalk-desktop/mac_dmg/Release/M1-Beta/DingTalk_v7.6.25_41241063_universal.dmg)

## 使用方法

```bash
# 运行脚本
python3 dingtalkrevoke.py
```

脚本会自动检测您的钉钉版本并应用相应的防撤回补丁。安装完成后，请重启钉钉以使更改生效。

## 致谢

感谢大佬的开源
<https://github.com/wuyoukm/MAC-DingTalkRevokeMsgPatcher>
