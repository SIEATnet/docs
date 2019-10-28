---
layout: default
title: CA-CASB-Salesforce
parent: Test
nav_order: 1
description: ""
---
# SIEAT.net Demo Updates
## Conditional access – CASB access to Salesforce from unmanaged device – download file – protect file
Maria accesses Salesforce through myapps portal with SSO on her managed device.
![Maria myapps portal](/assets/images/ca-casb-sf-01.png "Maria myapps portal")
![Maria Salesforce](/assets/images/ca-casb-sf-02.png "Maria Salesforce")
Please make sure, that you point out, that no CASB is used, because a managed device is used. Please navigate to Files in Salesforce. Maria has stored some relevant data there. Try to download one of the two Word files and the Excel file. Should work without hassle.
 
 
 
To demonstrate the different experience from a non-managed device, you can either use an in-private browser session on Marias corporate device or use your own device with a standard browser session.
Please do the same steps and access myapps portal and navigate to Salesforce.
 
After selecting Salesforce in the myapps portal you receive a conformation window, that access to Salesforce is montored, please press continue.
 
 
Please highlight the different domain used (*.cas.ms) because the session is proxied through MCAS. Afterwards navigate to Files and try to download one of the two Word files. Please remember, they were un-encrypted before.
Due to the applied MCAS policy, the word files get protected with AIP automatically and data loss to unmanaged devices can be restricted. If you demo this in the in-private browser session on Maria’s corporate device, you still can open the downloaded file in Word, but it is now secured with AIP. If you demo on your machine, you cannot open the file, as you have not a SIEAT.net managed device.
 
Additionally an alert is issued in MCAS and admin@sieat.net is informed via email. Afterwards please try to download the Excel file that contains credit card data. This file download is blocked by MCAS’ DLP engine, because of that sensitive data type on non-corporate devices.
 
Additionally an alert is again triggered in MCAS and an email is sent to admin@sieat.net.
In the MCAS console you see these alerts in the dashboard and further drill down.
 
 
If you check Activity Log you can additionally see all the tracked requests from the past demo and drill down.
 
Under Control > Policies you can additionally show both applied policies “[#khn] Session Control - Salesforce - protect file & download” and “[#khn] Session Control - Salesforce - Check for financial data & block download”.
 
 
Afterwards you can navigate to alerts and dismiss all entries.
 
