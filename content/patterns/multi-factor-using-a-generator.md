---
type: pattern

title: Multi-factor using a generator

images:
  - url: /images/multi-factor-with-generator.svg

alt: A code is generated on a device and entered into a computer.

category: Authentication

examples:
  - title: Two Factor Auth List
    url: https://twofactorauth.org/
    description: a directory of online services and whether they allow multi-factor authentication
  - title: Google Authenticator
    url: https://en.wikipedia.org/wiki/Google_Authenticator
    description: a mobile phone app that manages and generates codes for digital services
  - title: Yubikey
    url: https://www.yubico.com/products/yubikey-hardware/
  - description: Some banks provide code generators to customers when logging in to online banking
---

This type of [multi-factor authentication](https://en.wikipedia.org/wiki/Multi-factor_authentication) involves a person entering a code generated by an app or a device when requesting access to data.

The code is specific to that person and the device the code is generated on. It’s also single use and expires after a short amount of time. If the person enters a valid code, it is assumed that they have physical ownership over the nominated device that codes can be generated on.

Passwords can be guessed or stolen, so by requiring extra information sent to a device controlled by a particular person, it increases the confidence that the request to access data should be allowed.