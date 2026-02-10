## Detection as Code - Surrounding Traffic for Firewall Investigation

<img align="left" alt="MITRE ATT&CK Logo" width="120px" src="https://attack.mitre.org/theme/images/mitre_attack_logo.png"/>
<br/>

- [T1189 - Drive-by Compromise](https://attack.mitre.org/techniques/T1189/)

### Instructions

- Line 12
    - Can change according to the platform you have.
- Line 13
    - Comment this line in case you follow the next instruction item (Line 15).
- Line 15
    - Uncomment that and add the domain you want to investigate in case you already know which page is malicious; do that as a way to find out at what time the malicious page was visited so that you know what time to place the surrounding traffic.

<br/>
<img align="left" alt="Detections.ai logo" width="120px" src="https://detections.ai/detections-logo-navbar.svg"/>
<br/>

<p>This is for when we need to investigate user navigation through proxy logs to understand if visit was intentional or if it was a sideload (redirect/iframe/malvertising) causing the navigation.</p>

- [Link to the contribution](https://detections.ai/rules/019c226d-c36d-7233-a796-c95977ef5edb)
