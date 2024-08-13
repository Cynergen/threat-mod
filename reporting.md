# Threat Model Report
### Project Information
Project Name:  
Report Author:  
Date:  
Version:  

## STRIDE Threat Analysis

### Spoofing

| Identifier | Description | Mitigation |
|------------|-------------|------------|
| S1         | Voice commands are correctly tied to the owner or any voice? someone else could give the control commands. There must be a configuration to add trusted voices. |            |
| S2         |             |            |
| ...        |             |            |

### Tampering

| Identifier | Description | Mitigation |
|------------|-------------|------------|
| T1         | Attacker modifies victim's mobile phone to their phone so that they can access all their house data  | Session management must be securely implemented to avoid broken access control attacks |
| T2         |             |            |
| ...        |             |            |

### Repudiation

| Identifier | Description | Mitigation |
|------------|-------------|------------|
| R1         |             |            |
| R2         |             |            |
| ...        |             |            |

### Information Disclosure

| Identifier | Description | Mitigation |
|------------|-------------|------------|
| I1         | Communication between mobile and server must be encrypted (HTTPS) to protect against cleartext communication (MITM attacks)         |            |
| I2         | Communication between the security device and the server must be encrypted (HTTPS) to protect against cleartext communication (MITM attacks)  |            |
| I3        | Geolocation data must be securely stored |            |

### Denial of Service

| Identifier | Description | Mitigation |
|------------|-------------|------------|
| D1         | The hub that connects all the components of the security system fails (breaks, energy outage). If the smart locks were on, will they unlock? What happens? Can they be unlocked with a physical key in emergency situations?    |            |
| D2         |             |            |
| ...        |             |            |

### Elevation of Privilege

| Identifier | Description | Mitigation |
|------------|-------------|------------|
| E1         |             |            |
| E2         |             |            |
| ...        |             |            |
