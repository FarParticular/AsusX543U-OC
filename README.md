# OpenCore loader for Asus X543U(X540UBR)

### Laptop Hardwares

| Hardware      | Name                            |
|---------------|---------------------------------|
| Processor     | Intel Core I3-7020U             |
| Video card    | MX110(Not Working)/Intel HD 620 |
| Ram/ssd       | 8 GB/256 GB                     |
| Ethernet card | Athernos QCA9377(not working)   |
| Sound card    | ALC256(Layout: 5)               |

## ENG

---------

Sound card: ALC256(Layout 5), if the codec does not work, then find your codec on the [AppleALC](https://github.com/acidanthera/AppleALC/wiki/Supported-codecs) and write layouts until the codec works.

there are wifi kexts for usb ethernet card in the loader: RtWlanU.kext/RtWlanU127.kext. You can delete them and put your kext on the other wifi module

you will need to install the program from chris1111 and also see if your network card is in the [list](https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter)

------
A new bootloader update for the laptop will be released from the moment a new version appears.

----
## RUS

-------
Звуковая карта: ALC256(Значение: 5), если кодек или значение не работает то поищите свой кодек в [AppleALC](https://github.com/acidanthera/AppleALC/wiki/Supported-codecs) и пишите значение до того чтобы ваш кодек завелся

В загрузчике используются wifi кексты для свистулек по типу tplink, comfast. А именно: : RtWlanU.kext/RtWlanU127.kext

вам нужно будет установить программу от chris1111 и плюсом проверьте наличие своей свистульки в этом [репозитории](https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter)

----------
Выход нового релиза сборки загрузчика будет выходить по мере выхода релиза OpenCore. А именно в интервале 1-2 мес

----------
### ScreenShot/Скриншот:
![Photo](https://github.com/FarParticular/AsusX543U-OC/blob/main/Photos_and_Resources/Screen.png)

