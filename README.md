# WitteShadovv

I build privacy tooling for Linux and test what it leaves behind.

Cyber Security Engineer in Zürich. MSc in Information Security from Stockholm University. Mostly NixOS and Rust.

## Disclosures

**Brave: Tor window fetched sidebar favicons outside Tor.** Adding a page to the sidebar from a Private Window with Tor fetched its favicon from the real IP. Reported on HackerOne on 2026-09-24, fixed in Brave 1.96.60 on 2026-09-30 ([brave/brave-core#40214](https://github.com/brave/brave-core/pull/40214)) and credited in the [release notes](https://community.brave.app/t/release-channel-1-96-60/659016). [Write-up](https://witteshadovv.dev/notes/brave-tor-sidebar-favicon-leak/)

## Upstream

**nixpkgs · Portmaster.** Packaged the Portmaster application firewall and wrote its NixOS module ([NixOS/nixpkgs#442904](https://github.com/NixOS/nixpkgs/pull/442904)). I maintain both. [How to run it](https://witteshadovv.dev/notes/portmaster-on-nixos/)

## Projects

### [NAILS](https://github.com/WitteShadovv/nails)
Linux anti-forensics against offline disk examination. A hidden session on a decoy NixOS, Debian or Ubuntu system, entered with a soft-reboot. Alpha. Docs at [nails.run](https://nails.run).

### [deferred-apps](https://github.com/WitteShadovv/deferred-apps)
For NixOS and Home Manager. Apps show as installed but download on first launch, which keeps the host lighter.

## Research

[Toward Plausibly Deniable Dual-Environment Computing](https://urn.kb.se/resolve?urn=urn:nbn:se:su:diva-256198) ([PDF](https://www.diva-portal.org/smash/get/diva2:2065691/FULLTEXT01.pdf))  
MSc thesis, Stockholm University, 2026. The academic groundwork behind NAILS, with a forensic evaluation of what traces remain. I also [ran forensic tools against my own hidden environment](https://witteshadovv.dev/notes/forensic-residue-hidden-nixos/) and wrote down what leaked and what did not.

## Background

8+ years with Linux systems. 4 years in technical roles at ETH Zürich.

## Contact

Website: [witteshadovv.dev](https://witteshadovv.dev) · [Notes](https://witteshadovv.dev/notes/) · [RSS](https://witteshadovv.dev/rss.xml)  
General: [contact@witteshadovv.dev](mailto:contact@witteshadovv.dev)  
Security: [security@witteshadovv.dev](mailto:security@witteshadovv.dev) · [disclosure policy](https://witteshadovv.dev/security/)  
HackerOne: [witteshadovv](https://hackerone.com/witteshadovv)  
Keyoxide: [profile](https://keyoxide.org/aspe:keyoxide.org:6BBFZQKKZC4P4WXL7XOXIXWUOU)  
PGP: [key](https://witteshadovv.dev/pgp-key.asc) (`FCEB 73CE 73A7 00A8 8548 F25D CB4B BA75 1B7B 4D4D`)  
Signal: [chat](https://signal.me/#eu/-4fVVkAikVynNe0knOAb7JAU-EDKY2yAEMahwYYduwKHHjNfa9JGIoW9hq1ozEt6)  
Matrix: [@whiteshadow332:matrix.org](https://matrix.to/#/@whiteshadow332:matrix.org)
