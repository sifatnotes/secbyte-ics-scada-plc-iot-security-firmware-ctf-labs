# secbyte-ics-scada-plc-iot-security-firmware-ctf-labs
A practical collection of cybersecurity CTF labs covering Industrial Control Systems (PLC locked logic, SCADA sensor-to-safety architectures, network microsegmentation) and Internet of Things security (smart home breach forensics, IoT firmware extraction, device telemetry tampering, and baseline hardening).
# ICS/SCADA Architecture, PLC Logic Security, IoT Firmware & Smart Home Forensics CTF Labs

Welcome to the **ICS/SCADA Architecture, PLC Logic Security, IoT Firmware & Smart Home Forensics CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on industrial automation defense, programmable logic control, and consumer/enterprise Internet of Things (IoT) security—spanning **Industrial Control Systems & SCADA Architecture (PLC ladder logic manipulation, waterworks incidents, sensor-to-safety systems, Purdue model segmentation)**, **Foundational Security Thinking & IoT Baselines (Security mindset fundamentals, IoT vulnerability assessments, defensive baseline hardening)**, **Smart Home & Smart Campus Incident Response (Smart home breach exploitation, IoT traffic analysis, smart campus network breaches, IoT forensic triage)**, and **IoT Hardware & Firmware Analysis (Embedded hub recovery, binary firmware extraction, telemetry data parsing, hardware physical tamper analysis)**.

---

## Lab Collection Index

### 1. Industrial Control Systems (ICS), PLCs & SCADA Architecture
* **PLC Security: Locked Logic at Northwind Waterworks**  
  *Lab Link:* [https://learn.secbyte.org/ctf/plc-security-locked-logic-at-northwind-waterworks](https://learn.secbyte.org/ctf/plc-security-locked-logic-at-northwind-waterworks)  
  *Focus:* Analyzing Programmable Logic Controller (PLC) ladder logic downloads, identifying tampered logic blocks, bypassing unauthorized logic lockouts, and auditing water treatment valve controls.

* **Industrial Network Fundamentals: PLCs & Segmentation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/industrial-network-fundamentals-plcs-segmentation](https://learn.secbyte.org/ctf/industrial-network-fundamentals-plcs-segmentation)  
  *Focus:* Enforcing network segmentation across Purdue Model levels (Level 0-3), configuring OT jump hosts, isolating OT field bus communications, and auditing industrial firewall rules.

* **SCADA Architecture: From Sensors to Safety Systems**  
  *Lab Link:* [https://learn.secbyte.org/ctf/scada-architecture-from-sensors-to-safety-systems](https://learn.secbyte.org/ctf/scada-architecture-from-sensors-to-safety-systems)  
  *Focus:* Auditing complete SCADA signal paths—from field sensors/actuators to RTUs, HMIs, and Safety Instrumented Systems (SIS)—and identifying unencrypted sensor telemetry manipulation vectors.

<Image src="image_agent_tag_12679969332792124473" alt="Programmable Logic Controller unit interface diagram" caption="Industrial Programmable Logic Controller (PLC) Architecture" />

---

### 2. Cybersecurity Fundamentals & IoT Defensive Baselines
* **CS Fundamentals: Building Secure Thinking**  
  *Lab Link:* [https://learn.secbyte.org/ctf/cs-fundamentals-building-secure-thinking](https://learn.secbyte.org/ctf/cs-fundamentals-building-secure-thinking)  
  *Focus:* Developing core security mindsets, applying threat modeling frameworks (STRIDE/PASTA), establishing defense-in-depth principles, and evaluating attack surface boundaries.

* **IoT Security Assessment Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/iot-security-assessment-lab](https://learn.secbyte.org/ctf/iot-security-assessment-lab)  
  *Focus:* Executing end-to-end security assessments on connected devices, identifying unencrypted local communication APIs (MQTT/CoAP), and auditing cloud backend integrations.

* **IoT Hardening: From Default Passwords to Defensive Baselines**  
  *Lab Link:* [https://learn.secbyte.org/ctf/iot-hardening-from-default-passwords-to-defensive-baselines](https://learn.secbyte.org/ctf/iot-hardening-from-default-passwords-to-defensive-baselines)  
  *Focus:* Remediating weak factory default credentials, disabling unnecessary listening daemons (Telnet/UPnP), enforcing secure boot baselines, and hardening wireless IoT device configurations.

### 3. Smart Home, Smart Campus & IoT Network Forensics
* **Smart Home Security: From IoT Basics to Incident Response**  
  *Lab Link:* [https://learn.secbyte.org/ctf/smart-home-security-from-iot-basics-to-incident-response](https://learn.secbyte.org/ctf/smart-home-security-from-iot-basics-to-incident-response)  
  *Focus:* Understanding consumer smart home ecosystems, detecting unauthorized peripheral hub pairing, and establishing initial incident response containment protocols.

* **IoT Exploitation: Smart Home Breach Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/iot-exploitation-smart-home-breach-lab](https://learn.secbyte.org/ctf/iot-exploitation-smart-home-breach-lab)  
  *Focus:* Exploiting unauthenticated smart hub web interfaces, capturing cleartext Zigbee/Z-Wave radio packets, injecting rogue commands, and achieving remote code execution.

<Image src="image_agent_tag_12679969332792125922" alt="Smart home connected IoT architecture diagram" caption="Consumer & Smart Home Connected IoT Ecosystem Topology" />

---

* **IoT Forensics: Smart Home Incident Response**  
  *Lab Link:* [https://learn.secbyte.org/ctf/iot-forensics-smart-home-incident-response](https://learn.secbyte.org/ctf/iot-forensics-smart-home-incident-response)  
  *Focus:* Extracting volatile memory dumps and flash storage from compromised smart home gateways, parsing event logs, and reconstructing attacker lateral movement paths.

* **IoT Network Security: Smart Campus Breach**  
  *Lab Link:* [https://learn.secbyte.org/ctf/iot-network-security-smart-campus-breach](https://learn.secbyte.org/ctf/iot-network-security-smart-campus-breach)  
  *Focus:* Triaging widespread enterprise IoT compromises across a smart campus network, detecting rogue access points, isolating infected HVAC/lighting controllers, and enforcing 802.1X NAC.

### 4. IoT Firmware Analysis & Physical Hardware Forensics
* **IoT Firmware Analysis: SmartHub Recovery Case**  
  *Lab Link:* [https://learn.secbyte.org/ctf/iot-firmware-analysis-smarthub-recovery-case](https://learn.secbyte.org/ctf/iot-firmware-analysis-smarthub-recovery-case)  
  *Focus:* Unpacking binary firmware images (`binwalk`), carving SquashFS/JFFS2 file systems, reversing compiled C binaries using Ghidra, and recovering hardcoded encryption secrets.

* **IoT Device Analysis: From Telemetry to Tamper**  
  *Lab Link:* [https://learn.secbyte.org/ctf/iot-device-analysis-from-telemetry-to-tamper](https://learn.secbyte.org/ctf/iot-device-analysis-from-telemetry-to-tamper)  
  *Focus:* Analyzing IoT device telemetry feeds, detecting physical enclosure anti-tamper trigger events, inspecting PCB hardware components, and auditing hardware sensor inputs.

---

## Learning Path

### Path A: ICS/SCADA Defense & Automation Specialist
1. **SCADA Architecture & Segmentation:** Start with [SCADA Architecture](https://learn.secbyte.org/ctf/scada-architecture-from-sensors-to-safety-systems) and [Industrial Network Fundamentals](https://learn.secbyte.org/ctf/industrial-network-fundamentals-plcs-segmentation).
2. **PLC Logic Security:** Triage automation breaches in [PLC Security: Locked Logic](https://learn.secbyte.org/ctf/plc-security-locked-logic-at-northwind-waterworks).

### Path B: IoT Security Auditor & Penetration Tester
1. **Mindset & Assessment:** Start with [CS Fundamentals](https://learn.secbyte.org/ctf/cs-fundamentals-building-secure-thinking) and [IoT Security Assessment](https://learn.secbyte.org/ctf/iot-security-assessment-lab).
2. **Hardening & Exploitation:** Execute device audits in [IoT Hardening](https://learn.secbyte.org/ctf/iot-hardening-from-default-passwords-to-defensive-baselines) and [IoT Exploitation: Smart Home Breach](https://learn.secbyte.org/ctf/iot-exploitation-smart-home-breach-lab).

### Path C: IoT Firmware Specialist & Hardware Forensic Examiner
1. **Campus Network & Incident Response:** Triage breaches in [Smart Home Security](https://learn.secbyte.org/ctf/smart-home-security-from-iot-basics-to-incident-response), [IoT Forensics](https://learn.secbyte.org/ctf/iot-forensics-smart-home-incident-response), and [IoT Network Security](https://learn.secbyte.org/ctf/iot-network-security-smart-campus-breach).
2. **Firmware Carving & Hardware Tampering:** Reconstruct images and physical devices in [IoT Firmware Analysis](https://learn.secbyte.org/ctf/iot-firmware-analysis-smarthub-recovery-case) and [IoT Device Analysis](https://learn.secbyte.org/ctf/iot-device-analysis-from-telemetry-to-tamper).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding direct link to launch the exercise environment hosted on Learn SecByte.
3. Review scenario directives, PLC ladder logic files, IoT binary firmware images (`.bin`), PCAP network traces, or memory dumps.
4. Audit PLC logic blocks, extract SquashFS file systems using `binwalk`, analyze MQTT packet payloads, reverse-engineer smart hub binaries in Ghidra, or isolate infected campus IoT nodes to capture flags.

---

## Target Audience

* **ICS/OT Security Engineers & SCADA Administrators:** Audit PLC ladder logic, verify Purdue Model network segmentation, secure SCADA sensor-to-safety loops, and isolate industrial fieldbus networks.
* **IoT Security Researchers & Hardware Pentesters:** Unpack embedded firmware images, reverse-engineer smart hub binaries, analyze MQTT/CoAP protocols, and audit physical PCB tampering.
* **Incident Responders & Digital Forensic Examiners:** Conduct forensic analysis on compromised smart home gateways, parse IoT telemetry logs, and isolate infected smart campus endpoints.
* **Cybersecurity Students:** Acquire practical hands-on experience in OT industrial control systems, embedded hardware/firmware reverse engineering, and IoT network security.

---

## Disclaimer

All lab links provided in this repository direct to official training environments hosted on Learn SecByte. All materials and exercises are provided strictly for educational purposes, defensive skill building, and authorized security research. Unauthorized scanning, firmware reverse engineering, or industrial control system tampering against external production targets without explicit permission is strictly prohibited.
