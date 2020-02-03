仅翻译，原项目地址：https://github.com/matanki-saito/SimpleInstaller

# EU4DLL
这个 dll 使得在欧陆风云4中显示双字节字符成为可能.

## 注意
 - 这个项目是 **非官方的**.
 - macOS 是不支持的. 我甚至没有做的计划.
 - 只有Steam版是受到支持的.

## 如何使用
 1. 安装DLL. 我推荐 [simple installer](https://github.com/matanki-saito/SimpleInstaller).
 2. 订阅任何语言的语言包在Steam创意工坊上.
 3. 启动游戏. 👍

## Bug回报
如果你找到bug, 请从这个项目中**创建问题** . 
如果可能, 请用英语书写问题报告. 无论如何你也可以用你自己的语言来书写问题报告 (如日语, 韩语, 中文, 俄文等).

## 标准
### plugin.ini
待讨论/待定

### 自动升级
Plugin.dll 会自己更新. 更新会在游戏运行时且有互联网连接的时候进行. 如果你不需要或者玩离线游戏, 请删除 "plugins/autoupdate.bat" 文件.

### 命名顺序
将倒置问号（¿）附加到朝代中，名字和姓氏将颠倒.

```
1534.6.23 = {
  heir = {
    name = "Nobunaga"  # Nobunaga
    monarch_name = "Nobunaga"  # Nobunaga
    dynasty = "¿Oda"  # Oda 
    birth_date = 1534.6.23
    death_date = 1582.6.21
    claim = 90
    adm = 5
    dip = 5
    mil = 6
  }
}
# Nobunaga Oda -> Oda Nobunaga
```

当你使用一个分支时, 请将倒置的反问号（¿）从所有格式中移除。.

## 许可
MIT Licence

## 感谢
这个 dll 是从其他项目分支来的. 十分感谢. 

[EU4CHS](https://bitbucket.org/kelashi/eu4chs/src/master/)
