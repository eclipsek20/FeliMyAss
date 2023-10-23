# FeliMyAss
Experimental patch for attempting to enable FeliCa on Xiaomi 12 (in this case)

Expansion of my XDA Thread: https://xdaforums.com/t/osaifu-keitai-possible-felica-support-on-xiaomi-12-many-non-supported-modern-phones.4619715/

I have tried to decompile a Xiaomi 12T Pro JP ROM and a regular Xiaomi 12 EU ROM and merge certain NFC files

This repo is a result of this, the only thing it does is make google pay go from "this device is unsupported" to "SDK_FELICA_ERROR.MFI_UNKOWN_ERROR". Despite my failure I have learned a lot about Android ROMs in the process and will continue to work on this project if any ideas arise.

UPDATE (23/10/2023): By adding the file "NQNfcNci-v1" I was able to change the error to "8: SDK_FELICA_ERROR.OPEN_FAILED"

I still have some belief in my that there is a way to enable FeliCa, I just can't seem to find it today.

The file in the release section works with magisk and is bootable (at least for me), nearly all my eariler attempts produced a bootloop for some unknown reason, it didn't help that I realized quite late that the logcat provieded by TWRP is that of the bootup leading to the recovery.

If you have any suggestion/idea etc. feel free to start a issue 
