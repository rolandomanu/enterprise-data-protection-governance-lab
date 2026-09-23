Microsoft Purview Insider Risk Management Framework

Overview

This repository contains a structured framework, scenario designs, and triage workflows for implementing an Insider Threat Program using Microsoft Purview. The primary objective is to detect, analyze, and mitigate unauthorized data exfiltration and risky user behaviors while aligning security controls with organizational compliance standards (ISO/IEC 27001 and NIST CSF).

Core Components

01_Scenario_Design.md: Defines real-world high-risk user behaviors, such as data exfiltration prior to employment termination.

02_Purview_Indicators_Configuration.md: Outlines technical configurations, HR connector integration, and alert thresholds in Microsoft Purview.

03_Triage_Playbook.md: Step-by-step incident response and investigation workflow for security analysts.

Key Capabilities Addressed

Correlation of HR offboarding events with anomalous data access.

Detection of mass file downloads from SharePoint/OneDrive.

Monitoring of unauthorized removable storage (USB) transfers for classified assets.

Privacy-compliant alert triage and escalation paths.
