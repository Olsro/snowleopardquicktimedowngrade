# Downgrade internal QuickTime 2013 Components for Snow Leopard 10.6.8
Encode music with great quality for old devices after the installation of the 2013-004 Security Update which breaks it.

The aim of the package is to downgrade all of the affected files to their version prior to the security update.

# How to use
1) Install Snow Leopard with all updates excepted iTunes update
2) Install Pacifist for Snow Leopard: https://www.charlessoft.com/pacifist_olderversions.html
3) Download the pkg in this repo
4) Install iTunes 9.2.1 which is the last iTunes version that can take advantage of the old encoder: https://secure-appldnld.apple.com/iTunes9/061-8725.20100722.Bhnyt/iTunes9.2.1.dmg and install it. If your iTunes version has already been updated, I recommend to install the pkg using Pacifist to do it easily without making a mistake.
5) Profit. Importing CDs and converting to lossy will now be done using an encoder which is perfectly compatible with old devices without causing nasty sound articts when playing the sample on those devices only.

Recommended settings for transparency : 
- 128kbps VBR AAC for all other types of music
- 160kbps VBR AAC for classical music
If not sure and if you have enough disk space, encoding everything to 160kbps VBR AAC is very safe.

If you import CDs, don't forget to enable errors correction in the import settings menu of iTunes !

Only Clickwheel iPods and devices running a version below iOS 7 are affected by the software decoding issue. Also, Rockbox custom firmware is not affected by this issue. If you don't want to use a very old encoder, you can encode to AAC 256kbps to mask most of the artifacts on old devices or encode to ALAC.
You may also configure QuickTime 7.6.6 on Windows and take advantage of it using Foobar2000 to get much more flexibility for any of your convert needs.