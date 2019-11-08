---
layout: default
title: Security Admin's Experience Step 1
parent: Block malicious URLs via MDATP
nav_order: 1
---

# Security Admin's Experience Step 1 (Setup)
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Create a custom URL Indicator in Defender Security Center Portal

The Security Admin is using the Defender Security Center Portal to create a custom URL Indicator to block access to https://youtube.com.

![](/assets/images/scenario10/Scenario10_04.PNG "Create a custom URL Indicator in Defender Security Center Portal")

## URL Indicator settings

The Security Admin is able to choose to Allow / Alert only or Alert and block on the Indicator.

![](/assets/images/scenario10/Scenario10_05.PNG "URL Indicator settings")

## URL Indicator scoping

The Indicator can be scoped down to a subset of machines in the environment.

![](/assets/images/scenario10/Scenario10_06.PNG "URL Indicator scoping")

```scss
Note
It can take a while until this indicator is deployed to all machines.
```