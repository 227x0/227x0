> **Focused on SOC operations, incident response, and detection engineering.**

# Vladyslav Simonov

![Focus](https://img.shields.io/badge/Focus-SOC%20L1%2FL2-0f3460)
![Location](https://img.shields.io/badge/Ostrava%2C%20CZ-1a1a2e)
![Cases](https://img.shields.io/badge/SOC%20cases-4%20published-e94560)

![Stack](https://img.shields.io/badge/Wazuh%20SIEM-4.14-blue)
![Suricata](https://img.shields.io/badge/Suricata-IDS-red)
![Velociraptor](https://img.shields.io/badge/Velociraptor-EDR-green)
![Kali](https://img.shields.io/badge/Kali-rolling-557c94)
![Linux](https://img.shields.io/badge/Linux-Ubuntu%2FKali-yellow)

Computer Engineering graduate (**Professional Junior Bachelor**) moving into **cybersecurity**.
I learn by running a home SOC lab that mirrors a real L1 desk: SIEM, EDR, network IDS,
ticketing — and by attacking it myself from Kali.

## What I practice (hands-on, documented)

- **Full alert lifecycle**: attack → SIEM alert/archive → L1 triage → escalation ticket → response notes
- **Triage runbooks** for SSH brute-force, DNS anomalies, web attacks
- **Threat hunting in raw archives** when alerts don't fire (case: DNS exfiltration, 39 events / 0 alerts)
- **Bash tooling** for attack simulation (DNS exfil scripts, subdomain enumeration)
- **MITRE ATT&CK mapping** for every case

## Featured projects

### [soc-practice](https://github.com/227x0/soc-practice) — SOC cases from the home lab

| Case | Topic |
|---|---|
| [01](https://github.com/227x0/soc-practice/tree/master/cases/01-ssh-bruteforce) | SSH brute-force: attack → correlation rule 40112 → L1 escalation |
| [02](https://github.com/227x0/soc-practice/tree/master/cases/02-juice-shop-web-attack) | Juice Shop kill-chain: recon → SQLi → admin JWT → PII exfiltration |
| [03](https://github.com/227x0/soc-practice/tree/master/cases/03-lab-upgrade-arsenal-telemetry) | Lab upgrade: PD attack stack, auditd telemetry, custom Wazuh rules |
| [04](https://github.com/227x0/soc-practice/tree/master/cases/04-dns-exfiltration-hunting) | DNS exfiltration hunting: 0 alerts, found in archives, full triage |

### [soc-lab](https://github.com/227x0/soc-lab) — the infrastructure

Network design, detection pipeline, L1 operations (runbooks, incident register,
shift handover), ops runbook with real failure postmortems.

## Certifications

[![Cisco Networking Basics](https://img.shields.io/badge/Cisco-Networking%20Basics-049fd9)](https://www.credly.com/badges/bb4ab1ac-5b98-4099-b964-a76346a4ff40/public_url)
[![Cisco Introduction to Cybersecurity](https://img.shields.io/badge/Cisco-Intro%20to%20Cybersecurity-049fd9)](https://www.credly.com/badges/28eb2f86-a56d-4373-bb2c-2d0f683a0767/public_url)

<a href="https://www.credly.com/badges/bb4ab1ac-5b98-4099-b964-a76346a4ff40/public_url"><img src="cert-badges/networking-basics.png" height="95"></a>
<a href="https://www.credly.com/badges/28eb2f86-a56d-4373-bb2c-2d0f683a0767/public_url"><img src="cert-badges/introduction-to-cybersecurity.png" height="95"></a>
![NetAcad](https://img.shields.io/badge/NetAcad-Linux%20Unhatched%20(in%20progress)-1ba098)

## Languages

Українська · Русский · English · Čeština (daily use)
