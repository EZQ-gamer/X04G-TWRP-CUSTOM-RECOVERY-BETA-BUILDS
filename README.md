# X04G-TWRP-CUSTOM-RECOVERY-BETA-BUILDS
These are some prebuilds for the mi smart clock x04g global which doesn't work properly so if someone can fix it ,
Well I was surfering in internet yesterday when I found a ready twrp build for the mi smart clock x04g , I thought it would be a very interesting thing to do so I tried to flash it , sadly the file was too big for the clock's recovery partition and I flashed it instead on the temporary ram. It didn't work!! , I can't say that it is the developer's failure because the same developer made a LX04 TWRP build in the past , but as he wrote in the description he didn't flashed it or test it cause the flashing was hard , so I thought the problem was from the big file size . So I tried to make my own TWRP builds , I made one for it but it didn't work , I was thinking that the problem was from the custom rom Android 13 GSI it was running so I made one for Android 13 onto its stock recovery file. Both didn't worked I don't know why , it had kernel panics , bootloops and more . I got me diying cause I thought it would be great to see on a clock such this a custom recovery so I left the links if you want to try on stock or your lineage os X04G.
I used fastboot to flash the files so

1.The ready one that I found was too big so I flashed it using

fastboot boot <file.name.img>

2.The one I made based on TWRP 10 I used .

fastboot flash recovery <twrp.img>

3.I also made one based on TWRP 12.1-13 , I made it cause I use lineage OS 20 which is Android 13 so I thought there may be a problem so I used

fastboot flash recovery <twrpa13.img>

4.If it didn't work neither to you , here is the stock recovery file

fastboot flash recovery stock_recovery.img

or

with mtkclient gui or else

python3 mtk_gui.py or python3 mtk.py w recovery recovery.bin

Note!!

The mtkclient commands are like this on Linux Debian like Ubuntu which I used for it but you can also use windows mtkclient but I don't know the commands for it so you might research for the windows a bit

Please if you fixed it leave your img down below

Thank you ,

