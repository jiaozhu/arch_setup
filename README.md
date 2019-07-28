# Wythe's Arch Setup Script

> 用于自己在安装完 Arch Linux 之后对于 *i3wm* 桌面环境的配置以及常用软件的安装

## 安装:

```bash
curl -LO https://files.jiaozhu.blog/setup.sh
sh setup.sh
```

![虚拟机截图](https://files.tcpiptech.com/blog/arch_setup.png)

完事了 ：）

## 快捷键说明

### 1. 基础操作

- *$mod+Enter* : urxvt
- *$mod+Shift+Enter* : ranger
- *$mod+Shift+m* : ncmpcpp
- *$mod+Shift+q* : 退出
- *$mod+d* : rofi
- *$mod+Shift+c* : 重新加载 i3wm 配置文件
- *$mod+Shift+r* : 重启 i3wm
- *$mod+Shift+e* : 退出 i3wm
- *$mod+Shift+a* : 全屏幕截屏
- *$mod+Shift+p* : 当前应用截屏
- *$mod+Control+l* : 锁屏
- *$mod+Delete* : 关机、注销、重启相关

### 2. 导航

切换焦点

- *$mod+h* : 左
- *$mod+j* : 下
- *$mod+k* : 上
- *$mod+l* : 右

移动焦点

- *$mod+Shift+h* : 移动到左边
- *$mod+Shift+j* : 移动到右边
- *$mod+Shift+k* : 移动到上面
- *$mod+Shift+l* : 移动到下面

切换布局

- *$mod+b* : 水平布局
- *$mod+v* : 垂直布局
- *$mod+f* : 全屏
- *$mod+r* : 重置窗口大小

## 更新日志

- 增加 ibus-rime 输入法
- 增加 gucharmap
- 生成 XDG 目录
- 增加 neofetch