---
layout: default
title: AutoAIP-Sharing-MCAS
parent: Test
nav_order: 2

description: ""
---

## #2 Generate File – automatically becomes protected with AIP – share via OneDrive – Sharing is automatically removed by MCAS

Maria generates a new Word file with some content, that contains the phrase “Project SIEAT.net”. After saving this file to her OneDrive an AIP label is automatically applied.
 
 
Please note the automatically added header, watermark, label and encryption. Afterwards Maria wants to share this document to an external user, for example to your Microsoft e-mail address. To achieve that she right-clicks the recently generated file in Explorer and selects “Share”.
 
She doesn’t change “Anyone with link can edit” and selects “Copy Link” and copies the sharing link to her clipboard, as she wants to send the sharing invitation via Outlook. There she composes an email and sends it.
 
With the integration of AIP into MCAS the sharing link will be automatically removed in OneDrive and the file is moved to quarantine. Although the recipient receives the sharing invite via email, the sharing link is not valid anymore.
 
 
Maria as well receives a notification by CASB that the file was put into quarantine and the sharing link was removed. Additionally admin@sieat.net is informed via email as well.
 
When inspecting her OneDrive Maria sees that her original files were moved to the “Quarantine” folder an the original file was replaced through a text file.
 
When checking the MCAS console you can see the corresponding alert pop up.
 
By clicking the Option Menu of the quarantined file, you can select “Restore from user quarantine” to bring it back to Maria’s OneDrive.
 
Under Control > Policies you can additionally show the applied policy “[#khn] File - AIP - Remove sharing link”. In the Governance section you can highlight the actions that were taken to remediate the file sharing.
 




