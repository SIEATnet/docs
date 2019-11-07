---
layout: default
title: Maria's Experience
parent: 12 - Accessing corporate data via unmanaged Android device
nav_order: 1
---

# Maria's Experience
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Android 7 BYOD
Maria uses a BYOD Android 7 tablet. Just the out-of-the box Google Apps were installed during initial device setup. So she decides to use Gmail to access her corporate mailbox.

![](/assets/images/scenario12/Scenario12_03.PNG "Android 7")


## Setup corporate Mail Account in Gmail
Maria tries to setup mail account in Gmail

![](/assets/images/scenario12/Scenario12_04.PNG "Gmail signup 01")
![](/assets/images/scenario12/Scenario12_05.PNG "Gmail signup 02")

## No mailbox access in Gmail
As Gmail authenticates just as plain ActiveSync client without modern authentication, no access to her mailbox is possible due to the corporate security requirements.

![](/assets/images/scenario12/Scenario12_06.PNG "No mailbox access")

## Manual Outlook Mobile installation
Maria decides to install Outlook Mobile from Google Play Store manually, as it supports Modern Authentication.

![](/assets/images/scenario12/Scenario12_07.PNG "Install Outlook Mobile")
![](/assets/images/scenario12/Scenario12_08.PNG "Outlook Mobile uses modern authentication 01")

## Modern Authenication in Outlook Mobile
After entering her UPN Maria is redirected to her corporate login page for authentication.
![](/assets/images/scenario12/Scenario12_09.PNG "Outlook Mobile uses modern authentication 02")

## Mailbox access possible in Outlook Mobile
After a successful authentication, Maria is allowed to access her mailbox. Unfortunately, she cannot open the attached Word file, as she has no Word Mobile installed.

![](/assets/images/scenario12/Scenario12_10.PNG "Access to mailbox")

## Authentication in Word Mobile to access AIP protected content
After a successful manual installation of Word Mobile from Google Play Store, Maria is forced to enter her UPN.

![](/assets/images/scenario12/Scenario12_11.PNG "Word Mobile Authentication")

## Modern Authentication in Word Mobile
Again she is redirected to her corporate login page for authentication within Word Mobile.

![](/assets/images/scenario12/Scenario12_12.PNG "Modern Authentication")

## Successful rendering of AIP protected file
After a successful authentication Word Mobile renders the Azure Information protected Word file.

![](/assets/images/scenario12/Scenario12_13.PNG "Modern Authentication")