# MITRE ATT&CK Threat Intelligence Mapping

**SOC Analyst L1 Lab · Threat Intelligence · Adversary TTPs**

> 🟢 **Status: Active — mapping library is being expanded**

### 🧰 Stack
<img src="https://img.shields.io/badge/MITRE_ATT%26CK-000000?logo=mitreattack&logoColor=white" alt="MITRE ATT&CK"> <img src="https://img.shields.io/badge/Threat_Intelligence-555555" alt="Threat Intelligence"> <img src="https://img.shields.io/badge/TTP-Mapping-555555" alt="TTP Mapping">

## 🎯 Why I built this lab
To become comfortable using MITRE ATT&CK as a common language for describing attacker behaviour and connecting TTPs to detection data sources and mitigations.

## 🔎 Mapping workflow

1. Select an incident scenario or threat-actor behaviour set.
2. Break the activity into discrete attacker actions.
3. Map each action to the appropriate ATT&CK tactic and technique/sub-technique.
4. Identify useful detection data sources.
5. Document relevant mitigations and defensive controls.
6. Explain the reasoning behind each mapping.

## 🗂️ Mapping standard

| Scenario | Tactic | Technique | Detection source | Mitigation |
|---|---|---|---|---|
| Phishing / Initial Access | Initial Access | T1566 | Email/security gateway logs | User training, filtering, sandboxing |
| PowerShell Execution | Execution | T1059.001 | Process + PowerShell logs | Script Block Logging, application controls |

## 🧠 What I'm practising
**MITRE ATT&CK • threat intelligence • TTP mapping • detection data sources • mitigation research • adversary behaviour analysis**

## 📌 Evidence roadmap

The repository is being expanded with completed scenario mappings, screenshots and analyst notes. Mappings will be evidence-backed rather than generic technique lists.

## Scope & ethics
Educational threat-intelligence research using public or authorised material.
