Insider Risk Scenario Design: Pre-Departure Data Exfiltration

Objective

To proactively detect and contain intentional or accidental data theft by departing employees who possess authorized access to sensitive corporate assets (intellectual property, financial records, or PII).

Threat Profile & Indicators

When an employee enters an active offboarding window, the risk profile shifts significantly. The monitoring framework focuses on the following behavior sequence:

Trigger Event:

An employee submits a resignation or is marked for termination within the HR system, syncing an active status change through Microsoft Purview HR Connectors.

Anomalous Activity Phase:

Mass Cloud Access: A sudden spike in downloading files from SharePoint Online or OneDrive for Business outside of normal working hours.

Sensitive Label Interaction: Accessing, modifying, or downloading documents classified as Confidential or Restricted that the user does not typically interact with in their daily role.

Endpoint Exfiltration: Copying sensitive files to unmanaged USB drives or attempting to upload data to personal cloud storage services.

Risk Scoring & Policy Thresholds:

Purview aggregates these indicators to dynamically elevate the user's risk score. Once a defined threshold is breached, an automated alert is generated for the Security Operations Center (SOC) / Insider Risk team for investigation.
