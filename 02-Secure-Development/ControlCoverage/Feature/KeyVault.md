<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"  "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>

</head><body>
<H2>KeyVault</H2>
<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Description</th><th>ControlSeverity</th><th>Automated</th></tr>
<tr><td>Azure Active Directory applications, which have access to Key Vault, must use certificate to authenticate to Key Vault</td><td>High</td><td>Yes</td></tr>
<tr><td>Application must not share a Key Vault unless they trust each other and they need access to the same secrets at runtime</td><td>High</td><td>Yes</td></tr>
<tr><td>All users/identities must be granted minimum required permissions using Role Based Access Control (RBAC)</td><td>High</td><td>Yes</td></tr>
<tr><td>All Key Vault access policies must be defined with minimum required permissions to keys and secrets</td><td>High</td><td>Yes</td></tr>
<tr><td>Advanced access policies must be configured on a need basis</td><td>Medium</td><td>Yes</td></tr>
<tr><td>All Keys in Key Vault must be protected by HSM [Key Type = HSM Protected Key]</td><td>Medium</td><td>Yes</td></tr>
<tr><td>All Keys and Secrets in Key Vault must have expiration dates</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Diagnostics logs must be enabled with a retention period of at least 365 days.</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Restrict the cryptographic operations permitted using keys to the ones actually required</td><td>High</td><td>Yes</td></tr>
<tr><td>Key Vault owner must grant minimum required access to keys/secrets based on individual roles (Developer/Operator/Auditor/Security Team)</td><td>High</td><td>No</td></tr>
<tr><td>Keys/secrets must be rotated periodically</td><td>Medium</td><td>No</td></tr>
<tr><td>Diagnostic logs for Key Vault must be reviewed periodically</td><td>Medium</td><td>No</td></tr>
</table>
</body></html>
