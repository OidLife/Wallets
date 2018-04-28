# Wallets
#### Wallet downloads for Windows, Linux, and Mac OSx.

v1.0.0.0

#Windows wallet users notice:
-> https://github.com/OidLife/Windows.Defender

To download the wallet, click on the correct version for your operating system.

Mac OSx:
Find the file named:  
```opioid-qt.dmg```  
https://github.com/OidLife/Wallets/raw/master/opioid-qt.dmg

#### Note: *Mac wallets may experience splash image, logo and icon related issues.*


Linux:
Find the file named:  
```opioid-qt-linux.tar.gz```  
https://github.com/OidLife/Wallets/raw/master/opioid-qt-linux.tar.gz


Windows:
Find the file named:  
```opioid-qt-windows.zip```  
https://github.com/OidLife/Wallets/raw/master/opioid-qt-windows.zip


Once you have downloaded the correct file, just extract to your desktop and run the application.

### If you plan on re-compiling wallets from source, please make sure the seed nodes are pointed to:
1) `oidseednode1.net`
2) `oidseednode2.net`

Refer to /src/ -> net.cpp beginning @ line 1178

``static const char *strMainNetDNSSeed[][2] = {  
    {"oidseednode1.net", "oidseednode1.net"},  
    {"oidseednode2.net", "oidseednode2.net"},  
    {NULL, NULL}  
};``

Thank you,  
[OID Team](https://oid.life/)
