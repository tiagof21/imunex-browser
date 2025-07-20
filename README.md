<div align="center">
<img src="logo.png" alt="Imunex Browser" width="400px"/>
</div> 

# Imunex Browser

You should consider using Imunex Browser to: "<i>Make Chromium Great Again!</i>". Because sometimes "<i>less is more</i>". 

`Imunex Browser` was made by me. Therefore "<i>My Browser, My Rules!</i>". Fortunately, you can have your browser too and make you own rules! It's easy! Ask me how! ;)

`Imunex Browser` is a minimalist and hardened Chromium-based web browser.

`Imunex Browser` is free for personal use. It is not an open source project. 

`Imunex Browser` is not designed for developers/sysops due to it's default security concept, missing tools like Inspect/DevTools. For Developers I'd recommend using [Aloha Browser] or [Chromium Canary] or you can keep using your favorite one.

Don't expect to see any visual or exclusive feature from `Imunex Browser`, while 99% of the hardening is made under the hood. Actually, you will probably feel less trackers/ads annoying you while browsing the web and slightly more responsive when loading web pages (IMHO). You can test the browser perfomance on https://www.browserbench.org/ 

Optionally you can try one of our favorites background/themes (yet to be published).  

<div align="center">
<img src="images/ImunexBrowser_Installer_macOS.png" alt="Imunex Browser Installer for macOS" width="720px"/>
<p><sub>Imunex Browser Installer for macOS</sub></p>
</div>
<br>


The primary goal of `Imunex Browser` is to offer a secure and privacy-focused web browsing experience by eliminating features that, in my opinion, unnecessarily store and persist sensitive user data, however it is up to the user's choice to control - in practice, once those features are available and default enabled, user's are more likely to use. It is intentionally designed not to prompt the user to “save passwords” or store login credentials by disabling the built-in Password Manager and the "Offer to save password" feature.

This approach also extends to payment methods—which are disabled by default—since modern cyber threats increasingly target stored credentials and financial information. These features, originally introduced to enhance convenience, have now become common attack vectors. We believe that credential management should no longer be the responsibility of a web browser. Instead, users are encouraged to adopt dedicated tools such as password vaults or credential management solutions designed specifically for secure storage.

The Google Safe Browsing feature remains enabled by default to protect users from malicious sites and phishing attacks. However, because it involves the use of hashed data, users who prioritize maximum privacy may choose to disable it via the browser's Settings page.

<div align="center">
<img src="images/ImunexBrowser_macOS.png" alt="Imunex Browser Installer for macOS"/><br>
<p><sub>Imunex Browser 1.0.2 for macOS</sub></p>
</div> 
<br>


🏢 Imunex Browser Enterprise
`Imunex Browser Enterprise` offers multiple levels of advanced customization, far exceeding the privacy and security capabilities of the personal edition. In addition to enforcing strict privacy controls, it introduces powerful enterprise-grade security features aligned with the latest cybersecurity standards.

Your company can customize a wide range of features, from visual aspects to trusted certificate/devices, directory integration, compliance and content analysis.

Organizations can configure over 100 policy-based controls, deploy custom branding, and create a web browsing environment tailored to their specific operational and compliance needs. This level of control represents a significant advancement in managing corporate web access and security.

As a Google Partner Advantage member, we are also able to integrate other Google Cloud solutions, providing a unified, high-assurance cybersecurity approach through Chrome Enterprise and related tools. This enhances data protection and user privacy across your company’s digital environment.

📦 Enterprise Deployment & Custom Services
For commercial deployments, custom branding or tailored features, you will soon be able to Request a Service through the `Imunex Browser Enterprise` GitHub repository (coming soon). Until this you can contact directly by e-mail at: browser@imunex.ai

> Disclaimer: `Imunex Browser` was designed for my personal use, as well as, for my personal researches on TLS and Fingerprinting.
> Use of this tool is at your own risk. You assume full legal liability for its use, and the original author expressly disclaims any and all responsibility.
> There is no warranty of any kind, express or implied.
>
> Privacy questions?
> Please read: https://www.chromium.org/Home/chromium-privacy/

### User-agent and Fingerprints
| User-Agent and Fingerprints | Values                                                  |                     
|-----------------------------|---------------------------------------------------------|
| `User-agent:`               |                                   `ImunexBrowser/1.0.2` |
|                             |                                                         |
| `JA4 fingerprint:`          |                  `t13d1316h2_f4ad024020fe_0467e9cfe63c` |
|                             |                  `t13d1315h2_f4ad024020fe_5ec6092e2d4d` |
|                             |                  `t13d1517h2_8daaf6152771_7e51fdad25f2` |
|                             |                  `t13d1517h2_8daaf6152771_46b8896bec77` |
|                             |                                                         |
| `JA4H fingerprint:`         |   `ge11nr19enus_1a9a86a94233_000000000000_e3b0c44298fc` |
|                             |   `ge11cr19enus_1a9a86a94233_9a10d4221160_a5d0f178d304` |
|                             |   `ge11cr19enus_1a9a86a94233_9a10d4221160_43cb90553126` |
|                             |                                                         | 
| `PeetPrint fingerprint:`    |                      `2008c082cd02f2b26427c26a024c7ec6` |
|                             |                      `1d8b3a3b02c4ac13265c191d4be41932` |
|                             |                      `1d4ffe9b0e34acac0bd883fa7f79d7b5` |  
|                             |                      `c40650254882179bbf43bc623ad0afe5` | 
|                             |                                                         |            
| `Akamai fingerprint:`       |                      `52d84b11737d980aef856699f885ca86` |
-----------------------------------------------------------------------------------------

## Supported OS / Architectures / Tested On:
Linux *Debian 12* (x86_64) / MS Windows 11 (64-bit) (x86_64) / Apple macOS Sequoia (ARM64)

### Imunex 1.0.2 Releases Chromium base
| Chromium branch                            | OS/Architecture             |
|--------------------------------------------|-----------------------------|
| `Version 139.0.7213.0 (Dev Channel)`       |             `macOS (arm64)` |
| `Version 140.0.7272.0 (Dev Channel)`       |  `Linux Debian 12 (x86_64)` |
| `Version 140.0.7290.0 (Release Candidate)` |       `MS Windows (x86_64)` |
----------------------------------------------------------------------------

## Apple Notarization for macOS: 

"The Apple notary service is an automated system that scans Mac software for malicious content, checks for code-signing issues, and returns the results quickly. Notarizing your software assures users that Apple has checked it for malicious software and none was detected." [*]

```
  "jobId": "fb7827aa-XXXX-XXXX-XXXX-937f76f600d6",
  "status": "Accepted",
  "statusSummary": "Ready for distribution",
  "statusCode": 0,
  "archiveFilename": "ImunexBrowser-v10215-installer.dmg",
  "uploadDate": "2025-07-09T19:28:06.149Z",
  "sha256": "4bf79fc416db70ae86ba9c905046e7bf6553446b0ee06cf22fa710ff2dda5731",
```

[*] Read more: https://developer.apple.com/documentation/security/notarizing-macos-software-before-distribution

Linux and Windows versions are code-signed as well. To check signatures/certificates you can do:

On MS Windows: Installer and Application will be validaded automaticaly through the PKI.
On Linux: Import the public key (.pub) file and use the .sig file with `gpg`.  

```
gpg --import imunex-browser-v1.0.2-stable_140.0.7272.0-1_amd64.pub
gpg --verify imunex-browser-v1.0.2-stable_140.0.7272.0-1_amd64.deb.sig imunex-browser-v1.0.2-stable_140.0.7272.0-1_amd64.deb
```

To checksum the Releases, use the appropriate SHA256 hash.

## Features / non-Features

### Imunex Browser 1.0.2

| Enabled/Disabled features          | Personal  |  Enterprise |                           
|------------------------------------|-----------|-------------|
| Imunex Enforced Policies           |    ✅     |     ✅      |
| Disabled four TLS weak ciphers     |    ✅     |     ✅      |
| Disabled TLS RI (CVE-2024-23556)   |    ✅     |     ✅      |
| TLS Encrypted Client Hello (ECH)   |    ✅     |     ✅      |
| HttpsOnlyMode (forced_enabled)     |    ✅     |     ✅      |
| Drive                              |    ✅     |     ✅      |
| Disabled all TLS weak ciphers      |    ❌     |     ✅      |
| BuiltIn DNS Client                 |    ❌     |     ✅      |
| Enterprise ready                   |    ❌     |     ✅      |
| Client Certificate / SSO           |    ❌     |     ✅      |
| Parental control                   |    ❌     |     ✅      |
| Time control                       |    ❌     |     ✅      | 
| Screen lock                        |    ❌     |     ✅      |
| Quick Pin Unlock                   |    ❌     |     ✅      |       
| Printing control                   |    ❌     |     ✅      |
| Microsoft® Active Directory®       |    ❌     |     ✅      |
| Extensions Allow/Block list        |    ❌     |     ✅      |
| WebRTC Handling                    |    ❌     |     ✅      |
| Download Restrictions              |    ❌     |     ✅      |
| Content Analysis                   |    ❌     |     ✅      |
| Disabled Generative AI             |    ❌     |     ✅      |
| Remote Access                      |    ❌     |     ✅      |
| Remote Debugging                   |    ❌     |     ✅      |
| Browser reporting                  |    ❌     |     ✅      |
| Send To Your Devices               |    ❌     |     ✅      |
| Google API                         |    ❌     |     ✅      |
| Google Cast                        |    ❌     |     ✅      |
| Safe Browsing                      |    ✅     |     ❌      |
| Delete Browsing data               |    ✅     |     ❌      |
| Password Manager                   |    ❌     |     ❌      |
| Payment methods                    |    ❌     |     ❌      |
| Autofill with AI opt-in            |    ❌     |     ❌      |
| AutofillAiWithDataSchema           |    ❌     |     ❌      |
| Developer Tools                    |    ❌     |     ❌      |
| ImportAutofillFormData             |    ❌     |     ❌      |
| SearchSuggest                      |    ❌     |     ❌      |
| DefaultGeolocation                 |    ❌     |     ❌      |
| mDNS                               |    ❌     |     ❌      |
---------------------------------------------------------------

Here are some of the core Chrome Enterprise features and customizations available to enterprise customers.

For the Enterprise version all features can be managed, the features listed as ❌ does not means that it is not available, instead, it means that I do not recommend for a Enterprise web browser to have those features enabled. Depending on the companies needs, those features maybe make sense.
To read more visit https://chromeenterprise.google/intl/en_us/ (English) or https://chromeenterprise.google/intl/pt_br/ (Brazilian Portuguese).

## Contributing

These are very small changes in the source code of Chromium and this is the main reason that (for a while) the `Imunex Browser` will not be available at any Application Store. 
`Imunex Browser` does not have scheduled updates or upgrades or any kind of technical support for the personal use version, however changes and/or proprietary features can be released without annoucement.
If you want to share ideas, request features or request a feature removal let us know.

## Sponsors & Donation

`Imunex Browser` is sponsored by Rezolvnet Soluções em Informática Ltda.

<div align="center">
<img src="images/logo_rezolvnet.png" alt="Rezolvnet Logo" width="120px" />
</div> 

Consider supporting `Imunex Browser` (personal).
Due to the costs of time-consuming customization, hardening, tests, Apple Developer Program, digital certificates and building/releasing (time/energy/hardware) we are accepting donations.

Donate using <a href="https://www.paypal.com/donate/?hosted_button_id=FVU6FH6FE739L">Paypal</a>

Or scan the QR code:

<div align="center">
<img src="images/donation-qrcode.png" alt="Donate to Imunex Browser (personal)" width="240px"/>
</div> 
<p align="center">
<br>
Thank you!
</p>

## Contact

```
browser@imunex.ai
https://imunex.ai
```

## MISC
> `As any binary file the releases of Imunex Browser are not reproducible. Binary installers inherently embed build‐specific metadata—timestamps, compiler and linker 
> paths, file‐order in archives, compression headers, GUIDs, and code‐signing signatures—that vary with each build environment or invocation. Because these values differ > even when the source is identical, the resulting installer binaries cannot be reproduced bit-for-bit.`

## Motivation and Future work
`Imunex Browser` was motivated by a series of well-known and unknown web browser's, but this is a looong story. 
I am working on a new Imunex proprietary feature for `Imunex Browser Enterprise` for macOS.


# ![Logo](https://github.com/chromium/chromium/blob/main/chrome/app/theme/chromium/product_logo_64.png) About Chromium

Chromium is an open-source browser project that aims to build a safer, faster,
and more stable way for all users to experience the web.

The project's web site is https://www.chromium.org.

To check out the source code locally, don't use `git clone`! Instead,
follow the instructions on [how to get the code] (<a href="https://github.com/chromium/chromium/blob/main/docs/get_the_code.md">docs/get_the_code.md</a>).

Documentation in the source is rooted in (https://github.com/chromium/chromium/blob/main/docs/README.md)(docs/README.md).

Learn how to [Get Around the Chromium Source Code Directory
Structure] (https://www.chromium.org/developers/how-tos/getting-around-the-chrome-source-code).

For historical reasons, there are some small top level directories. Now the
guidance is that new top level directories are for product (e.g. Chrome,
Android WebView, Ash). Even if these products have multiple executables, the
code should be in subdirectories of the product.

If you found a bug, please file it at https://crbug.com/new.
