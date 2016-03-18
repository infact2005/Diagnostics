# Diagnostics

Grub
title Diagnostics
find --set-root /bzImage
kernel /bzImage
initrd /initrd

initrd~\initrd~~\opt\telegon 

sdcram_misc100.ld
sdcram_tp40100.ld
sspb_sdc_prim422.ld
ATMdesk2_Key_Device402.ld - usb dongle (flash + smartcard) - Нужно вмсето него мой ридер с офф ключем

Устройство производителя:
ATMdesk GmbH ATMdesk2 Key Device	Составное USB устройство	Неизвестно	Нет	Да	Нет	Нет	 	_0002367	17.03.2016 16:16:39	13.10.2015 19:30:18	10c4	c0de	4.02	00	00	00	 	 	Cygnal Integrated Products, Inc.	 	2&53a7d5d&0	usbccgp	Драйвер универсального родительского устройства USB (Microsoft)	usbccgp.sys	USB	(Стандартный USB хост-контроллер)	 	 	Составное USB устройство	6.1.7601.17514	USB\VID_10C4&PID_C0DE\_0002367
0000.001d.0007.002.001.000.000.000.000	Устройство чтения смарт-карт Microsoft Usbccid (WUDF)	Смарт-карта	Нет	Нет	Нет	Нет	 	 	17.03.2016 16:16:40	31.08.2015 8:23:53	10c4	c0de	4.02	0b	00	00	 	 	Cygnal Integrated Products, Inc.	 	8&1cf0da22&0	WUDFRd	 	WUDFRd.sys	SmartCardReader	Microsoft	 	 	Устройство чтения смарт-карт Microsoft Usbccid (WUDF)	6.1.7601.17514	USB\VID_10C4&PID_C0DE&MI_00\7&19bf5e35&0&0000

Мое:
Smart Card Reader USB	Устройство чтения смарт-карт Microsoft Usbccid (WUDF)	Смарт-карта	Нет	Нет	Нет	Нет	 	 	17.03.2016 16:16:39	06.08.2015 1:16:30	076b	3021	3.02	0b	00	00	 	 	OmniKey AG	CardMan 3121	2&1cd42d5&0	WUDFRd	 	WUDFRd.sys	SmartCardReader	Microsoft	 	 	Устройство чтения смарт-карт Microsoft Usbccid (WUDF)	6.1.7601.17514	USB\VID_076B&PID_3021\1&2d12bed1&0&1
