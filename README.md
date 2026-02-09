<h1>Detection as Code</h1>

<h2>Surrounding Traffic for Firewall Investigation</h2>

<h3>MITRE ATT&CK</h3>

- [T1189 - Drive-by Compromise](https://attack.mitre.org/techniques/T1189/)

<h3>Instructions</h3>

- Line 12

    - Can change according to the platform you have.

- Line 13

    - Comment this line in case you follow the next instruction item (Line 15).

- Line 15

    - Uncomment that and add the domain you want to investigate in case you already know which page is malicious; do that as a way to find out at what time the malicious page was visited so that you know what time to place the surrounding traffic.

- [Link to Detections AI](https://detections.ai/rules/019c226d-c36d-7233-a796-c95977ef5edb)

<p>This is for when we need to investigate user navigation through proxy logs to understand if visit was intentional or if it was a sideload (redirect/iframe/malvertising) causing the navigation.</p>