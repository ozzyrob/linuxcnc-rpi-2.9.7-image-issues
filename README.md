# linuxcnc-rpi-2.9.7-image-issues Trixie Based

Issues relating to linuxcnc-2.9.7 Trixie based RPi images.  
Do not post issues to emc user threads, I'm unable to be a member.  
Forum isn't a good place either, I rarely visit any more.   
__Please use latest image before posting issues, which is RC4.__   
I'll only be supporting from version rc4 & later, if you are running earlier versions please upgrade to the latest.  
Also in any issues please post which version you are currently running, if you are running anything earlier than the latest,  
which could be updated, please go to the latest version. ATM the moment I'm only assigning each release as release candidates as
this is a new build system, and to save space, not add bloat or services that are not required I've had to modify what is  
included and not included.  
The more that can help the faster the image can get to a stage where it does what it should.  
I do implore you to download the notes that are linked to in the release section.  
__Please use Rpi Imager 1.9.6 as this allows customisations to image__  
https://github.com/raspberrypi/rpi-imager/releases/tag/v1.9.6

---
# Linuxcnc RPi images shipped with 2.9.2 Bookworm Base

Not discussed here, please see the following links
* Main Thread https://forum.linuxcnc.org/9-installing-linuxcnc/55192-linuxcnc-the-raspberry-pi-4-5-official-images-only
* Index to Main Thread https://forum.linuxcnc.org/38-general-linuxcnc-questions/55767-index-to-linuxcnc-the-raspberry-pi-4-5-official-images-only

---

# RC4 Release 12 December 2025

* Fixed loss of custom splash, by same mechanism for fixing Linuxcnc menu entries
* Fixed first boot wizard issue (piwiz)
* power manager and screensaver disabled from autorun
* dpms & screen blanking disable via autorun entries
* Unresolved issue with Rpi Imager 2.0.x for customising image __Not recommended__
* Please report any issues __NOT__ to Forum, but to https://github.com/ozzyrob/linuxcnc-rpi-2.9.7-image-issues
* Packages will be current from image build date
* __It has been noted that the hal_gpio driver is not built for the Linuxcnc packages used in this iamge, this an issue we need the Linuxcnc devs to look at.__
* So until this is resolved I can not see a fix for this, __if one does require the hal_gpio driver it is advised to stick with the previous Bookworm image__.

[RC4 Image](https://drive.google.com/file/d/1CoO_2y7iDTwtubGpODlHlRf_z27LbVSw/view?usp=sharing)

[md5Sum](https://drive.google.com/file/d/1iI4AibzRT-T0X2gK2htuv4VeMxkAdFpj/view?usp=sharing)

[Notes.txt](https://drive.google.com/file/d/118QtxZVqIYyoCtjdPIn09c5woxRIDk1u/view?usp=sharing)
