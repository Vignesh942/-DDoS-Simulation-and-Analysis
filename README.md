# DDoS-Simulation-and-Analysis

A concise proof-of-concept showing a controlled TCP SYN flood simulation in a lab environment. The goal is to demonstrate attack behavior, capture traffic, validate detection with Snort, and provide simple, practical mitigations.


# Quick summary

Attack type: TCP SYN flood (Hping3)

Tools used: Hping3, Wireshark, Snort, tcpdump

Test environment: isolated lab (Kali attacker, Ubuntu target)

Key outcome: Snort detected SYN flood patterns; Wireshark capture confirms high SYN rate. Recommendations include SYN cookies, rate limiting, IDS tuning, and upstream mitigations.

## Visit Documentation for more Info
