<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"  "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>

</head><body>
<H2>CDN</H2>
<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Description</th><th>ControlSeverity</th><th>Automated</th></tr>
<tr><td>All users/identities must be granted minimum required permissions using Role Based Access Control (RBAC)</td><td>Medium</td><td>Yes</td></tr>
<tr><td>CDN profile endpoints must use token authentication</td><td>Medium</td><td>No</td></tr>
<tr><td>Token encryption key must be protected in a key vault (when a website generates tokens via code).</td><td>High</td><td>No</td></tr>
<tr><td>CDN endpoints must use HTTPS protocol while providing data to the client browser/machine or while fetching data from the origin server</td><td>High</td><td>Yes</td></tr>
<tr><td>Do not put any sensitive data in a CDN. CDN is suitable only for resources where anonymous access is not a concern</td><td>High</td><td>No</td></tr>
<tr><td>Configure real time alerts on status code 403 to be observant of any unauthorized request for CDN endpoint</td><td>Medium</td><td>No</td></tr>
</table>
</body></html>
