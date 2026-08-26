# MITRE ATT&CK Threat Intelligence Mapping

Mapping of observed attacker behaviors and simulated incident scenarios to the MITRE ATT&CK framework, with reference documentation linking tactics/techniques to detection and mitigation strategies.

## 🎯 Objective

To build fluency in the framework SOC teams use as a common language for describing attacker behavior — moving from "something bad happened" to "this is Initial Access via T1566 Phishing, followed by T1059 Command and Scripting Interpreter."

## 🧰 Reference Framework

- [MITRE ATT&CK Enterprise Matrix](https://attack.mitre.org/matrices/enterprise/)

## 🔧 Methodology

1. **Scenario Selection**
   - Selected incident scenarios from *<!-- e.g. LetsDefend/CyberDefenders cases, or a constructed attack chain -->*
2. **Behavior Identification**
   - Broke down each scenario into discrete attacker actions (e.g. initial foothold, lateral movement, exfiltration)
3. **ATT&CK Mapping**
   - Mapped each identified behavior to its corresponding Tactic (e.g. Initial Access, Execution, Persistence) and Technique/Sub-technique ID
4. **Detection & Mitigation Research**
   - For each mapped technique, documented relevant data sources for detection (e.g. process creation logs, network traffic) and applicable mitigations from MITRE's guidance

## 📋 Mapping Table

| Scenario | Tactic | Technique (ID) | Detection Data Source | Mitigation |
|---|---|---|---|---|
| *<!-- e.g. Phishing → PowerShell execution -->* | Initial Access | Phishing (T1566) | Email gateway logs | User training, attachment sandboxing |
| *<!-- e.g. same scenario, next stage -->* | Execution | Command and Scripting Interpreter: PowerShell (T1059.001) | Process creation logs, PowerShell logging | Script block logging, constrained language mode |
| *<!-- add more rows for each scenario you mapped -->* | | | | |

*<!-- Replace with your actual mapped scenarios -->*

## 🔍 Example: Full Attack Chain Mapping

*<!-- Pick one scenario and walk it end-to-end as a worked example -->*

**Scenario:** *<!-- brief description -->*

```
Initial Access (T1566)
   → Execution (T1059.001)
      → Persistence (T10XX)
         → ...
```

**Notes:** *<!-- why each stage maps to that technique, and what a defender would look for at each stage -->*

## 🧠 Skills Demonstrated

- Applying the MITRE ATT&CK framework to real/simulated incidents
- Translating raw attacker behavior into structured threat intelligence
- Understanding detection data sources per technique
- Connecting technique-level knowledge to actionable mitigations

## 📚 What I Learned

*<!-- 3-4 sentences: which tactic category was hardest to map correctly, how this changed the way you read incident reports, why a shared framework like ATT&CK matters for SOC communication -->*

## 🔗 Related

Part of a 5-project SOC Analyst portfolio. See also: [SOC Alert Triage Practice](https://github.com/Ravi-KYadav/soc-alert-triage-practice) · [Network Traffic Analysis](https://github.com/Ravi-KYadav/network-traffic-analysis-wireshark-suricata)
