### This fork adds a new option to the settings:

* BOOT INTO
  * EZ MENU  - the console boots into the menu as normal
  * NOR GAME - the console boots directly into the first game in NOR memory, if there is one
* You can hold L while the console is powering to boot into the alternate option

---

#EZ-FLASH OMEGA Kernel

### How to build 

    1.We use devkitARM_r47, you can use the current version or newer.
    2.Set the following environment variables in system, or modify the value in build.bat, based on your installation path
 
        PATH,DEVKITARM,DEVKITPRO,LIBGBA

    3.Double click on build.bat under winodws. If it goes well, you will get ezkernel.gba
    4.Rename the ezkernel.gba to ezkernel.bin, that is the omega kernel upgrade file