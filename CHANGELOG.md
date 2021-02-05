v0.6.5
- Passive automated mirror setup at GitLab <https://gitlab.com/AnonymousPlanet/thgtoa>
- Added Donation Monero address within the guide
- Added README/Guide mention to the GitLab mirror
- Changed CHANGELOG to CHANGELOG.md for GitHub Pages integration
- Updated GPG key with GitLab noreply e-mail for commit verification
- Added sitemap on GitHub Pages for SEO
- Added latest version, changelog and alternative pdf download links on Github Pages
- Verified site on Keybase

v0.6.4
- Improved HTML layouts for better readability and SEO
- Added redirect from <https://anonymousplanet.github.io> to the guide page
- Fixed README to to include hyperlinks

v0.6.3
- Added Table of Contents to PDF formats for better readability
- Fixed Appendixes/Sections references in the Markdown/HTML format
- Moved target-audience disclaimer from introduction to start of document
- Small layout fixes

v0.6.2
- Various little kramdown glitches fixed in HTML format
- Small fixes in spelling/grammar
- Added a small disclaimer in the introduction to let people know they can just read the first 26 pages to learn about the various threats without the need for practical applications

v0.6.1
- Various endnotes layout fixes
- Added OSINT YouTube Playlist reference
- Added reference to Whonix Live Host OS documentation (Similar to HiddenVM project)
- Added Twitter account (If it lasts, it was already suspended three times) <https://twitter.com/AnonyPla>. I'd be grateful if you share/like my tweet about this guide.

v0.6.0
- Various small spelling/grammar/layout fixes
- Added various references to Whonix Documentation (Hardening, Anti-Forensics, Anti-Evil Maid...)
- Added one Bellingcat reference to a recent case
- Added some Qubes OS references (Anti-Evil Maid and Hardening)
- Added new sub-route to the TAILS route using the HiddenVM project <https://github.com/aforensics/HiddenVM> for providing Plausible Deniability within TAILS

v0.5.9
- Added Monero accepting VPS providers as options for self-hosting cloud services and self-hosting VPN services

v0.5.8
- Added various references to Whonix documentation (anti-forensics, cold boot attack defenses, full disk encryption)
- Small various fixes
- Added reasoning for not supporting M1 Macs
- Added Acknowledgements at the end of the guide
- Added some resources to cold-boot, evil-maid defenses

v0.5.7
- Added methods to check Trim/ATA/NVMe operations on external SSDs
- Added methods to securely delete data on Qubes OS

v0.5.6
- Added donations/sponsorship support to this project using Monero
- Added reference to Law Enforcement surveillance capabilities (CCC video)
- Added guidance to remove some forensic traces from MacOS 
- Added guidance to remove some forensic traces from Linux (log deletion and trim)
- Added variants for securely erasing SSD drives (only ATA drives were mentioned, added specific info for NVMe drives).
- Added lists of laptop brands supporting Secure Erase (SSD) from BIOS/UEFI.
- Changed recommendation from GParted to System Rescue instead due to GParted not providing nvme-cli by default. 
- Fix: Multiple fixes in SDD/HDD sections (layout, duplicate data...)
- Fix: Multiple fixes in SDD secure erasing section and added various warnings for various methods
- Fix: Removed blkdiscard from wrong section and from MacOS as it's not supported on MacOS by Homebrew
- Various spelling/grammar fixes

v0.5.5
- Added passphrase recommendations (xkcd.com) in the OPSEC section and other sections.

v0.5.4
- Added more information and mitigation possibilities for CPU exploits on Virtual Machines (Spectre, Meltdown...)

v0.5.3
- Added guidance to hidden containers with plausible deniability in the backup section
- Added guidance for online backups
- Added information for VPN kill switches for Whonix, MacOS and Linux

v0.5.2
- Update of GPG key (added no-reply e-mail) to get verified commits

v0.5.1
- Small various fixes

v0.5.0
- Added Watermarking section in threats with pictures/videos/audios watermarks and printer watermarks within

v0.4.9
- Various small spelling/grammar/layout fixes
- Added some Laptop recommendations and more info about Libreboot and Coreboot
- Added various references to key disclosure laws 
- Added guidance to create a mat2-web guest Debian VM for removing metadata from files conveniently
- Changed CHANGELOG to markdown for integrating into GitHub Pages

v0.4.8
- Various fixes on spelling/grammar and layout
- Various fixes on KeepassXC sections for Linux/MacOS
- Added hardening recommendations for Virtualbox
- Added VPN installation tutorials for Linux/MacOS

v0.4.7
- added Virtualbox workaround for Spectre/Meltdown issue mitigation
- added section and guidance to remove metadata from various files and tools
- added reference to Haven app for physical security in OPSEC section
- added recommendation to use systematic TOTP 2FA for online identities when possible
- added references to Deepfakes, facial recognition and fingerprint recognition in biometric threats

v0.4.6 Added link to Shodan to Smart Devices Section, Full rewrite of data wipe sections (especially SSDs)

v0.4.5 Improved SSD/HDD erasure section and some spelling fixes.

v0.4.x Added Backup methods, OPSec tricks, Malicious USB, Printers and various fixes

v0.3.x Added MacOS information and various fixes

v0.2.x Added Qubes OS information and various fixes

v0.1.x Initial Release (missing Qubes OS details and MacOS support)
