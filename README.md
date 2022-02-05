# CUSTOMIZED SEABIOS PKGBUILD SCRIPT 


<br>

<p align="center"> 
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/issues/Nexusflipp/seabios-sfbuild"/> </a>
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/languages/top/Nexusflipp/seabios-sfbuild"/> </a> 
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/languages/count/Nexusflipp/seabios-sfbuild"/> </a> 
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/last-commit/Nexusflipp/seabios-sfbuild"/> </a> 
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/repo-size/Nexusflipp/seabios-sfbuild"/> </a> 
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/languages/code-size/Nexusflipp/seabios-sfbuild"/> </a> 
</p>

<br>


This PKGBUILD script installs a slightly customized version of Seabios.
SeaBIOS is an open source implementation of a 16bit X86 BIOS. SeaBIOS can run in an emulator or it can run natively on X86 hardware with the use of coreboot.

SeaBIOS is the default BIOS for qemu and kvm. 

<br>

Building
========

First cd into the project directory, then run the following command:

```shell
makepkg -s -i --skippgpcheck --skipchecksums
```
  
<br>  

Documentation
=============

The official documentation is available here: https://seabios.org/SeaBIOS.
