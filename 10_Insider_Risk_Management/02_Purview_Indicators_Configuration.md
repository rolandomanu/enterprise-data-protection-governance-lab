Microsoft Purview Indicators & Policy Configuration

1. HR Data Integration (HR Connectors)

To establish contextual awareness, Microsoft Purview requires synchronization with organizational human resources data.

Data Schema Setup: Map core attributes including UserPrincipalName, TerminationDate, ResignationDate, and EmploymentStatus.

Sync Schedule: Configure automated daily imports to ensure real-time adjustments to employee risk profiles when a departure notice is logged.

2. Policy Scope & Indicator Selection

Configure the Insider Risk Management policy targeting high-risk departments (e.g., R&D, Finance, Executive Leadership):

Content Indicators: Enable detection for items labeled with custom sensitivity labels (Confidential, Restricted).

Exfiltration Indicators:

Exfiltration by departing users (triggered by HR resignation date).

High volume of file deletions or mass downloads from SharePoint Online.

Copying files to removable media (USB) correlated with endpoint DLP logs.

3. Threshold Tuning

Low Risk: Single isolated event of sensitive file access outside normal hours.

Medium Risk: Multiple files downloaded combined with unusual cloud activity.

High Risk: Mass download sequence executed by a user with an active HR offboarding flag. Escalates automatically to alert status.
