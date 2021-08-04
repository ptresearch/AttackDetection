Suricata PT Open Ruleset
=====
The [Attack Detection Team](https://twitter.com/AttackDetection) searches for new vulnerabilities and 0-days, reproduces it and creates PoC exploits to understand how these security flaws work and how related attacks can be detected on the network layer. Additionally, we are interested in malware and hackers’ TTPs, so we develop Suricata rules for detecting all sorts of such activities. 
## Structure
This repository consisting of folders with self-explanatory names contains Suricata rules, PoC exploits, and traffic samples in zip archives with default password.

:wrench: Some rules in this repo are aimed to detect communications under TLS. Please, set ```encryption-handling: full``` in suricata.yaml configuration file to activate them.
## SID range
We use SID 10000000-11999999 for our rules.
## License
This software is provided under a custom License. See the accompanying LICENSE file for more information.
