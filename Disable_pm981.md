# How to Disable Non Working PM981 on hackintosh

`diskutil list`

get the disk partition identifier you want to disable on you hackintosh
the following is my PM981
```
/dev/disk1 (internal):
   #:                       TYPE NAME                    SIZE       IDENTIFIER
   0:      GUID_partition_scheme                         512.1 GB   disk1
   1:       Microsoft Basic Data SYS                     512.1 GB   disk1s1
```

then check the Disk/partition UUID

`diskutil info #youridentifier#`

`sudo vifs`
it will open a vim editor,

write this line at the bottom of the opened text file:

`UUID=#the id you get from last step# none ntfs noauto `

save and exit 

and you are good to go!

reference:
https://www.tonymacx86.com/threads/how-to-disable-specific-nvme-m-2-slot-via-dsdt-hide-unsupported-970-evo-plus.275416/
thanks a lot!
