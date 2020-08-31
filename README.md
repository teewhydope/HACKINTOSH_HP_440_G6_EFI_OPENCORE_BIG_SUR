| Specification | 	Details                                        |
|-------------- |--------------------------------------------------|
| Model         |   HP Probook 430/440/450 G6 Laptops              |
| OS 	          |   macOS Big Sur 11.0 Beta (20A5354i)             |
| Processor 	  |   Intel(R) Core(TM) i7-8565U CPU @ 1.80GHz       |
|Memory 	      |   16 GB ( Kingston DDR4 2667MHz )                |
| Hard disk 	  |   (256 GB / NVME)                                |
|Graphic card 	|   Intel UHD Graphics 620                         |

--------------------------------------------------------------------------------------------------------------------------------
**Everything works fine**
--------------------------------------------------------------------------------------------------------------------------------
**INSTALLATION GUIDE**

**(1)** Download the full offline installer using this script  [installScript_110fullapp.zip](https://github.com/teewhydope/HACKINTOSH_HP_PROBOOK_440_G6_OPENCORE_EFI/files/5145360/installScript_110fullapp.zip)

**(2)** Choose the latest version, Big Sur

**(3)** Install Normally, You will have few reboots so be patient. you might get stuck at **Forcing CS_RUNTIME for entitlement: com.apple.rootless.restricted-block-devices**, just be patent...

--------------------------------------------------------------------------------------------------------------------------------
**Make sure you remove voodoohid,voodooinput and voodooi2c and leave just voodoops2controller if you get a kernel panic**

I added **XHCI-UNSUPPORTED.KEXT** to enable the camera

Make sure you set **alcid=3** in boot-args, if you have to sound input/output (will fix applealc)

Generate a new serial
--------------------------------------------------------------------------------------------------------------------------------
**Minor issueS**
Clover Congigurator doesn't work very well
Mouse lag at password input page
Make sure you set the ctrl, fn and alt button at keyboard settings and also the mouse tracking speed





