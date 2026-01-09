# ShellCrash-custom-rules
ShellCrash自定义在线配置规则模版

# 使用方法
1.新增一条在线配置规则模版
```
vi /data/ShellCrash/configs/server.list
# 新增条目
500 Acl4SSR分流&游戏&去广告增强Custom https://github.com/tw3nty-1/ShellCrash-custom-rules/raw/main/rules/custom_rule_ShellClash_Full_Block.ini (Custom_Full_Block)
520 Acl4SSR全能优化版Custom https://github.com/tw3nty-1/ShellCrash-custom-rules/raw/main/rules/custom_rule_ShellClash.ini (Custom)
```
2.进入ShellCrash并修改在线配置规则模版(crash - 6 - 1 - 0 - 4 - 20 - 1 )
```
root@XiaoQiang:~# crash
-----------------------------------------------
欢迎使用ShellCrash！            版本：1.9.4beta1.1
Mihomo服务正在运行（混合模式），已设置开机启动！
当前内存占用：53.96 MB，已运行：00小时00分13秒
TG频道：https://t.me/ShellClash
-----------------------------------------------
 1 启动/重启服务
 2 功能设置
 3 停止服务
 4 启动设置
 5 设置自动任务
 6 管理配置文件
 7 访问与控制
 8 工具与优化
 9 更新与支持
-----------------------------------------------
 0 退出脚本
 ```
 ```
请输入对应数字 > 6
```
```
-----------------------------------------------
 ShellCrash配置文件管理
-----------------------------------------------
 1 在线生成配置文件(基于Subconverter订阅转换)
 2 在线获取配置文件(基于订阅提供者)
 3 本地生成配置文件(基于内核providers,推荐！)
 4 本地上传完整配置文件
 5 设置自动更新
 6 自定义配置文件
 7 更新配置文件
 8 还原配置文件
 9 自定义浏览器UA
-----------------------------------------------
 0 返回上级菜单
 ```
 ```
请输入对应数字 > 1
```
```
-----------------------------------------------
检测到已记录的链接内容：
https://${url}$
-----------------------------------------------
```
```
清空链接/追加导入？[1/0] > 0
```
```
-----------------------------------------------
 欢迎使用在线生成配置文件功能！
-----------------------------------------------
-----------------------------------------------
本功能依赖第三方在线subconverter服务实现，脚本本身不提供任何代理服务！
严禁使用本脚本从事任何非法活动，否则一切后果请自负！
-----------------------------------------------
支持批量(<=99)导入订阅链接、分享链接
-----------------------------------------------
 1 开始生成配置文件（原文件将被备份）
 2 设置节点过滤关键字
 3 设置节点筛选关键字
 4 选取在线配置规则模版
 5 选取在线生成服务器
 0 撤销输入并返回上级菜单
-----------------------------------------------
```
```
请直接输入第1个链接或对应数字选项 > 4
```
```
-----------------------------------------------
当前使用规则为：Acl4SSR全能优化版(推荐)
 1      Acl4SSR分流&游戏&去广告增强Custom(Custom_Full_Block)
 2      Acl4SSR全能优化版(推荐)
 3      Acl4SSR精简优化版(推荐)
 4      Acl4SSR全能优化+去广告增强
 5      Acl4SSR极简版(适合自建节点)
 6      Acl4SSR分流&游戏增强
 7      Acl4SSR分流&游戏&去广告增强(低性能设备慎用)
 8      洞主规则精简版
 9      洞主规则重度完整版
 10     Acl4SSR多国精简
 11     Acl4SSR回国专用
 12     Acl4SSR增强国外GFW(适合黑名单模式使用)
 13     DustinWin全分组规则
 14     DustinWin无广告全分组规则
 15     DustinWin精简规则(推荐)
 16     DustinWin无广告精简规则
 17     DustinWin黑名单模式规则
 18     DustinWin无广告黑名单模式规则
 19     DustinWin轻量规则
 20     DustinWin极简规则
 21     Acl4SSR全能优化版Custom(Custom)

-----------------------------------------------
0 返回上级菜单
```
```
请输入对应数字 > 1
```
```
-----------------------------------------------
设置成功！返回上级菜单
-----------------------------------------------
本功能依赖第三方在线subconverter服务实现，脚本本身不提供任何代理服务！
严禁使用本脚本从事任何非法活动，否则一切后果请自负！
-----------------------------------------------
支持批量(<=99)导入订阅链接、分享链接
-----------------------------------------------
 1 开始生成配置文件（原文件将被备份）
 2 设置节点过滤关键字
 3 设置节点筛选关键字
 4 选取在线配置规则模版
 5 选取在线生成服务器
 0 撤销输入并返回上级菜单
-----------------------------------------------
```
```
请直接输入第1个链接或对应数字选项 > 1
```
```
-----------------------------------------------
链接地址为： 链接地址为：https://sub.jwsc.eu.org/sub?target=clash&ua=clash.meta/mihomo/v1.19.17&insert=true&new_name=true&scv=true&udp=true&exclude=&include=&url=${url}&config=https%3A%2F%2Fgithub.com%2Ftw3nty-1%2FShellCrash-custom-rules%2Fraw%2Fmain%2Frules%2Fcustom_rule_ShellClash_Full_Block.ini

可以手动复制该链接到浏览器打开并查看数据是否正常！

已成功获取配置文件！
```
```
是否启动服务以使配置文件生效？(1/0) > 1
```
```
-----------------------------------------------
服务已启动！
请使用 http://192.168.2.1:9999/ui 管理内置规则

```

<strike>
# 使用方法
1.在线生成地址
```
# 在线生成地址,需对机场${url转义}
https://sub.jwsc.eu.org/sub?target=clash&ua=clash.meta/mihomo/v1.19.17&insert=true&new_name=true&scv=true&udp=true&exclude=&include=&url=${url}&config=https%3A%2F%2Fgithub.com%2Ftw3nty-1%2FShellCrash-custom-rules%2Fraw%2Fmain%2Frules%2Fcustom_rule_ShellClash_Full_Block.ini
```
2.下载文件，访问生成地址，另存为config.yaml,上传到服务器
```
/tmp/ShellCrash/config.yaml
```
</strike>

# 更新内容
2026.01.09  update  新增 Acl4SSR分流&游戏&去广告增强 配置（source：[ShellClash_Full_Block.ini](https://github.com/juewuy/ShellCrash/blob/dev/rules/ShellClash_Full_Block.ini)）

2026.01.09  create  因人工智能节点无直连（关闭代理）选项，所以修改该配置文件（source：[ShellClash.ini](https://github.com/juewuy/ShellCrash/blob/dev/rules/ShellClash.ini)）