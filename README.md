# Hackintosh_guide黑苹果





## Build Parts

| ****     | ****      |
| ----------  | --------------------------- |
| **CPU**     | **Intel Core i5 8500**      |
| **Mobo**    | **AsRock z370M Pro4**       |
| **Mem**     | **24GB ADATA DDR4 2666MHz** |
| **Storage** | **Normal SATA SSD & 2t HDD**|
| **GPU**     | **NVIDIA Geforce GTX 970**  |

  

## 重要的注意事项！！
### 即使在bios中没有enable intel optane 内存，也一定要拆下Optane内存，不然会无法启动hackintosh。

## 2019-02-13 update:



最后选择了安装Mac OS high Sierra 10.13.6

因为这是coffee Lake 支持的最低版本，SMBIOS 的设备名要不能选择Mac mini 2018 ,因为不支持10.13。



安装10.13.6的重要原因是在之前使用intel iGPU安装中出现vram错误，尝试了能找到的各种方法，仍没有解决。故使用nvidia 独显。10.14不支持nvidia 显卡，故放弃Mojave。

## 2019-04-06 updata:
根据reddit上的网友回答：interl iGPU vram 错误的原因是使用了非dp接口。




kexts和configlist都按照valina的方法来的，usb接口方面，用3.0安装没有遇到问题。

参考有：

<https://hackintosh.gitbook.io/-r-hackintosh-vanilla-desktop-guide/>



<https://www.youtube.com/watch?v=Eeq5WvolPwE&index=6&t=0s&list=PLwlWHSKkxmotTafDOqFieOFFpchUtQUSY>

最后能够顺利地从disk中的clover引导进入macOS，安装对应build版本的webNVIDIAdriver就ok啦！

## 这是最后的样子，改了名字 just for fun.

![Screen Shot 2019-02-13 at 17.09.24](https://github.com/ljllili23/Hackintosh/blob/master/Screen%20Shot%202019-02-13%20at%2017.09.24.png)


