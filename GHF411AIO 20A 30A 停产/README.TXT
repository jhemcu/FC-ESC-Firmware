根据现在BF的更新固件方式，固件是由公共程序HEX和配置文件组成的，所以需要先刷入HEX文件后，
在进入到BF中，此时飞控没有任何反应，没有陀螺仪和加速度计，这样还需进入到CLI选项，将配置文件中的内容全部复制，
并粘贴到CLI里面，按回车键，这样才完成了整个刷固件的操作。

HEX文件随着BF团队的更新，版本也会更新，我们这里上传的只是做参考，为了指导您不要刷错固件和配置文件，需要最新的BF固件，可以进入：
HEX下载：https://github.com/betaflight/betaflight/releases
配置文件下载：https://github.com/betaflight/unified-targets/tree/master/configs/default
