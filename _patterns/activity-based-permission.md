---
layout: pattern

title: Activity-based permission

category: Control access

images:
- url: /images/activity-based-permission.svg

alt: A mobile phone is tilted, putting it in to sleep mode.

advantages:
 - Remains convenient while offering some form of security

limitations:
 - Matching sensor data to actual activity can be error prone
 - Can’t prove identity through activity

examples:
  - title: Do Not Disturb Apple iOS
    url: https://support.apple.com/en-gb/HT208090
  - title: Smart Lock Android
    url: https://support.google.com/nexus/answer/6093922?hl=en-GB

open-source:
  - title: User activity
    url: https://github.com/KrauseFx/user.activity

---

Controlling access to data based on what someone is currently doing. Devices could guess what a person is doing using sensors like gyroscopes, accelerometers or GPS. For example, a phone could automatically lock when it senses it’s on a table.
