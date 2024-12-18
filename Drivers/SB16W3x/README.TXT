README.TXT
==========

This file contains additional information to supplement the 
manual.  Please read all the sections before you proceed with 
the installation.


This file contains the following sections:

   1.  DOS drivers 
   2.  Blaster line
   3.  Online documentation


1. DOS DRIVERS 

   During custom installation, you have the options to include the 
   following DOS drivers to your CONFIG.SYS file.

       DEVICE=C:\SB16\DRV\CTSB16.SYS /UNIT=0 /BLASTER=A:220 I:5 D:1 H:5
       DEVICE=C:\SB16\DRV\CTMMSYS.SYS

   where :

   BLASTER=A:220 I:5 D:1 H:5 indicates the hardware resources used
   by your audio card.

   The CTSB16.SYS driver has been improved to support different
   models of audio cards.  The BLASTER switch will not have any
   effect if you are using a Plug and Play audio card.  For such
   cards, the hardware resources will be allocated by the PnP
   Configuration Manager.  In this case, PnP Configuration Manager
   has to be loaded before your DOS audio drivers.


2. BLASTER LINE

   The BLASTER line in your AUTOEXEC.BAT file,

       SET BLASTER=A220 I5 D1 H5 P330 T6

   will not have any effect if you are using a Plug and Play audio 
   card for the same reason as above.


3. ONLINE DOCUMENTATION

   To help you access information on the applications in this package
   easily, we have compiled the online documentation so that it can be
   accessed from your audio card's group window. Just click on the
   icon(s) with names that start with the words "How to Use".


                 ******** END OF README.TXT ********
