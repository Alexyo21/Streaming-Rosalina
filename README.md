# Streaming-Rosalina
adds streaming capabilities back to custom luma3ds.
since on old console this would break compatibilities of the cfw i removed it and made a separate version only for new 3ds the feature are listed on luma page:
https://github.com/Alexyo21/CustomLuma3DS
remember only new3ds version console...
thanks to byebyesky

* to use it copy it as it is into /luma/sysmodules folder and enable load external modules and firmware in cofig menu.
only new 3ds

for building set enableenforcedebug and disabledbug on what you need, if you are Compiling debug set
-DisableDebug: false
-EnableEnforceDebug: true

and compile with the flag 
make all "DEBUG=1"

For release set that flags in the opposite way and compile with make all.

discord link:
https://discord.com/invite/qR2D3dq43b