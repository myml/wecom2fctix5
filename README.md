# wecom2fctix5

在线生成企业微信群成员的姓名词库

<ul>
    <li>打开企业微信公司群</li>
    <li>点击群成员列表旁边的菜单按钮</li>
    <li>使用“复制群成员账号”功能</li>
    <li>粘贴群成员账号到 https://we2fctix5.pages.dev 里面的输入框</li>
    <li>点击转换按钮，保存转换好的文本文件 worker.txt </li>
    <li>在命令行使用 sudo apt install libime-bin 安装命令行工具</li>
    <li>在命令行使用 libime_pinyindict worker.txt ~/.local/share/fcitx5/pinyin/dictionaries/worker.dict 转换文本文件为词库文件
    </li>
    <li>重启 fctix5</li>
</ul>

感谢: 
- https://github.com/zh-lx/pinyin-pro
- https://wiki.archlinuxcn.org/zh/Fcitx5
- https://github.com/fcitx/libime
