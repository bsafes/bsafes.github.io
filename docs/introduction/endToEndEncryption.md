---
layout: page
title: End-to-End Encryption 
parent: Introduction
nav_order: 20 
---


# End-to-End Encryption 
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What does it mean? 

![](https://statics.bsafes.com/endToEndEncryptionDiagram.png)
End-to-End Encryption means no one between Alice and Bob could know the content of their communication. In above illustration, the thick black line means encrypted data between Alice and Bob from end to end.

![](https://statics.bsafes.com/withoutEndToEndEncryptionDiagram.png)
Without End-to-End Encryption, service provider in the middle(e.g. Google, Evernote, Onenote) could know the content exchaged between Alice & Bob. In above illustration, there are 2 thick black lines,one between Alice & service provider, another one between service provider & Bob. Even though data is encrypted between Alice and service provider, likewise, encrypted between service provider and Bob, the service provider decrypts and can see the data in plain text.

Most service providers claim Encryption at Rest, which means they decrypt users data, process(e.g. index), then encrypt users data again before storing them in database or storage. Therefore, they know content of users data.

## How does End-to-End Encryption work in BSafes?
