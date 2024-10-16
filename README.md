# How to block Nintendo System / Firmware updates   


you need to add this in default.txt in the hosts folder in atmosphere folder on your SD card. 


#block nintendo updates\
127.0.0.1 receive-%.dg.srv.nintendo.net receive-%.er.srv.nintendo.net\
sun.hac.%.d4c.nintendo.net\
atumn.hac.%.d4c.nintendo.net\
127.0.0.1 sun.hac.lp1.d4c.nintendo.net\
127.0.0.1 atumn.hac.lp1.d4c.nintendo.net


then make sure you enable dns mitm 

add those in your system_settings.ini in folder config in your atmosphere folder on your SD card. 

[atmosphere]\
enable_dns_mitm = u8!0x1\
enable_dns_mitm_debug_log = u8!0x1\




