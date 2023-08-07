# WixShenanigans

requires both wix 3 and wix 4

### instructions:

build the 3 msi projects
 - BootMSIwixThree
 - BootMSIwixThree2
 - BootMSIwixFour

build the two bundles
 - BootstrapperWixTHREE
 - BootstrapperWixTHREEupgraded

preferably using a virtual machine
 - install "BootstrapperWixTHREE" (WixShenanigans\BootstrapperWixTHREE\bin\Debug\BootstrapperWixTHREE.v1.0.001.exe)
 - check "Add or Remove Programs". the package along with the msi should be listed
   ![image](https://github.com/tm-nti/WixShenanigans/assets/90686450/4ee0a420-37a0-4fd9-b320-1f3572ce7ade)

 - install "BootstrapperWixTHREEupgraded" (WixShenanigans\BootstrapperWixTHREEupgraded\bin\x64\Debug\BootstrapperWixTHREE.v1.0.002.exe)
 - check "Add or Remove Programs". the package is there but the msi's are missing

### note: 

"BootstrapperWixTHREEupgraded" is the upgraded project of "BootstrapperWixTHREE" and has the same upgradecode and the same msi's

"BootstrapperWixTHREEupgraded" has a version higher than "BootstrapperWixTHREE" and is an installation upgrade to "BootstrapperWixTHREE"
