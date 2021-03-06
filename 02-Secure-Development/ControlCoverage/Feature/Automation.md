<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"  "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>

</head><body>
<H2>Automation</H2>
<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Description</th><th>ControlSeverity</th><th>Automated</th></tr>
<tr><td>All users/identities must be granted minimum required permissions using Role Based Access Control (RBAC)</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Webhooks should not be used for runbooks that perform highly sensitive functions</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Webhook URL must have a shorter validity period (&lt;= 60 days) to prevent malicious access</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Encryption of Automation account variable assets must be enabled when storing sensitive data</td><td>High</td><td>Yes</td></tr>
<tr><td>Never hardcode secure information in your runbook, instead use Automation account assets (Credentials, encrypted variables etc.)</td><td>High</td><td>No</td></tr>
<tr><td>Automation account keys should be rotated periodically as per the company standards</td><td>Medium</td><td>No</td></tr>
<tr><td>Credentials for Run As Account should be deleted and recreated at regular intervals to make sure that Service Principal connection credentials are not compromised</td><td>Medium</td><td>No</td></tr>
<tr><td>Automation account having Hybrid Runbook Worker feature configured must have only limited/required assets added, since on-premise machines running the MMA (Microsoft Monitoring Agent) have access to all the Automation account assets</td><td>Medium</td><td>No</td></tr>
<tr><td>Runbook authentication must be done using dedicated service principal instead of AD User account </td><td>Medium</td><td>No</td></tr>
<tr><td>Configure Log Analytics to get greater operational visibility of your Automation jobs</td><td>Medium</td><td>No</td></tr>
</table>
</body></html>
