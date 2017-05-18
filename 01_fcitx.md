#fcitx
##配置fcitx
```
$ im-config         //input method configuration
```
1. 打开输入法配置后，OK，OK将fcitx设置为默认输入法
2. 重启使配置生效
    ```
    sudo reboot  
   ```
   
3. 安装谷歌拼音
    ``` shell
    sudo apt install fcitx-googlepinyin
    ```
4. 设置fcitx输入法
    ```apple js
    fcitx-config-gtk3
    ```
5. **ctrl+space** 或者 **ctrl+shift** 切换输入法

