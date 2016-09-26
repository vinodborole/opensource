---
layout: post
title: "OTP Library"
date: 2016-08-23 16:54:46
author: Abdul Waheed
categories:
- blog
- Authentication
- Code-Snippets
img: OTP_Library.png
thumb:
---

Many organizations today still struggle with providing strong authentication for their web-based applications. Most organizations continue to rely solely on passwords for user authentication, which tend to be weak (to be easy to memorize), shared across systems, etc. Though there have been strides towards strong authentication mechanism like 2FA, adoptance has been low.<!--more-->

It gives me immense pleasure to announce that GS Lab is open sourcing its OTP Library asset. Abdul Waheed from GS Lab was instrumental in developing this asset, which is a standards based library that enables organizations to adopt One Time Password (OTP) based Two Factor Authentication (2FA) for Java/J2EE business critical applications, leading to improved security posture. It supports HMAC-based One Time Password (HOTP) and Time-based One Time Password (TOTP) standards and works with the free, off-the-shelf Google Authenticator mobile app to provide a friendly user experience.
 
#### Features
* Java/J2EE based library - used on server side
* Standards based support (HOTP and TOTP)
* Supported client - Google Authenticator
* Ability to generate QRCode (to be scanned by Google Authenticator)
* Integration with server is simple, straightforward requires minimal effort
* Support for security features like throttling, look ahead, encryption, etc.

#### Key Benefits
* Add 2FA to existing Java/J2EE server applications
* Standards compliant (HOTP and TOTP standards support)
* Minimum integration overhead
* Small footprint
* Leverage existing free off-the-shell Google Authenticator Mobile app
* Already adopted by market leaders like AWS for 2FA needs.
* User friendly experience using QRCode
* No costs associated with SMS/Text messaging and no related software requirements.

It is open source and can be easily downloaded from GitHub. Thank you Abdul for your contributions in making this happen!
