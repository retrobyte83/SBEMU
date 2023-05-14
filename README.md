# SBEMU
Sound blaster emulation with OPL3 for AC97.

Supported Sound cards:
 * Intel ICH / nForce
 * Intel High Definition Audio
 * VIA VT82C686, VT8233
 * SB Live/Audigy

The VT82C868 & ICH4 are tested working on real machine.\
ICH & HDA tested working in virtualbox, not verified on real machine yet.\
HDA tested working by community.

Emulated modes/cards:\
8 bit & 16 bit DMA (mono, stereo, high-speed)\
Sound blaster 1.0, 2.0, Pro, 16.

Requirements:
 * HDPMI32i (HDPMI with IOPL0) (https://github.com/crazii/HX)
 * QEMM (optional, used for real mode games) or JEMM (https://github.com/Baron-von-Riedesel/Jemm)
 
SBEMU uses some source codes from:
 * MPXPlay: https://mpxplay.sourceforge.net/, for sound card drivers
 * DOSBox: https://www.dosbox.com/, for OPL3 FM emulation
