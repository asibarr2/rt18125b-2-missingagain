# rt18125b-2-missingagain

This is for a missing firmware in Nvidia-Driver 460 for Issac Sim

- mkdir rtl8125b_fw
- cd rtl8125b_fw
- wget https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/plain/rtl_nic/rtl8125b-2.fw
- wget https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/plain/rtl_nic/rtl8168fp-3.fw
- sudo cp *.fw /lib/firmware/rtl_nic/
- sudo update-initramfs -u
