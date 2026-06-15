# wuxiannuannuan-whimstar-cursors
无限暖暖主题鼠标指针（奇想星版） / Infinity Nikki theme cursors (whimstar)


## 预览 / Preview
<img width="1168" height="640" alt="preview" src="https://github.com/user-attachments/assets/f983bc66-2579-4010-b1c0-3c91527a7b97" />


## 项目内容 / Project Overview
以在《无限暖暖》中的奇想星的形象和元素为原型，由StarryCursor设计并制作，包含10种鼠标状态。
其中MAC支持 32 / 64 / 160 / 320 多分辨率，Windows支持 32 / 48 / 64 / 96 / 128 多分辨率


## 安装 / Installation
### MAC：
1. 下载并安装 [Mousecape](https://github.com/alexzielenski/Mousecape/releases)
2. 打开 Mousecape，菜单栏 `Mousecape` → `Install Helper Tool`
3. 下载本仓库的 [无限暖暖-02-v5.cape](https://github.com/StarryCursor/wuxiannuannuan-cursors-whimstar-/blob/main/%E6%97%A0%E9%99%90%E6%9A%96%E6%9A%96-02-v5.cape) 文件
4. 双击 .cape 文件导入到 Mousecape
5. 右键导入的 cape → `Apply`
6. （ps: 这套鼠标细节比较多，颜色比较浅，建议将指针大小调大一号，使用感更好哦）
   
### Windows:
1. 下载本仓库的zip [无限暖暖-02-Windows-v5.zip](https://github.com/StarryCursor/wuxiannuannuan-cursors-whimstar-/blob/main/%E6%97%A0%E9%99%90%E6%9A%96%E6%9A%96-02-Windows-v5.zip) 解压
2. 右键单击 install.inf (Windows 11 用户：先点"显示更多选项"或按 Shift+F10)
3. 在菜单里点"安装"
4. 弹出 UAC 权限请求时，点"是"
5. 按 Win+R 输入 main.cpl 回车，打开"鼠标 属性"
6. 切换到"指针"标签
7. 在"方案"下拉框里选"无限暖暖-02"
8. 点"确定"，所有 10 个光标立即生效（若无法批量生效，可以找到鼠标指针一个一个自定义修改）
9. （ps: 这套鼠标细节比较多，颜色比较浅，建议将指针大小调大一号，使用感更好哦）

【常见问题】
- 右键菜单里找不到"安装"？
  Windows 11 需要先点"显示更多选项"，或按 Shift+F10 调出旧版菜单。
- UAC 弹窗一闪就消失？
  可能是账户不是管理员，或被杀毒软件拦截。
  切换到管理员账户重试，或临时关闭杀毒软件。
- 下拉框里没看到"无限暖暖-02"？
  可能是 INF 没装上。试试用管理员身份打开 cmd，
  cd 到 INF 所在目录，运行：
    rundll32.exe setupapi.dll,InstallHinfSection DefaultInstall 132 .\install.inf
  
【包含的 10 个光标】
- arrow.cur          正常箭头
- ibeam.cur          文本选择
- link.cur           链接选择
- busy.cur           忙碌 / 工作中
- size_ns.cur        垂直调整 ↕
- size_we.cur        水平调整 ↔
- size_nesw.cur      对角调整 2 (NE-SW) ↗↙
- size_nwse.cur      对角调整 1 (NW-SE) ↖↘
- closedhand.cur     拖拽（Windows 标准方案不含此槽位）
- 每个 .cur 内嵌 5 种分辨率 (32/48/64/96/128)，自适应 100%~300% 显示缩放。

【卸载】
1. Win+R 输入 main.cpl，"方案"下拉框选"Windows 默认"
2. 用管理员身份打开 cmd，运行:
   rmdir /S /Q "%SystemRoot%\Cursors\NuanNuan-01"
   reg delete "HKCU\Control Panel\Cursors\Schemes" /v "无限暖暖-02" /f


## 致谢 / Credits
- 角色设计基于游戏《无限暖暖》（Infinity Nikki，© Papergames / Infold Games）
- 本仓库仅为同人爱好分享，不用于商业用途


## License
本仓库的代码部分采用 CC0 / MIT 协议。但角色形象版权归原作者所有，使用请遵守原作版权方的规定。
