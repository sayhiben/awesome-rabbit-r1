<!--lint disable no-undefined-references-->
<!--lint disable awesome-toc-->

# Awesome Rabbit R1 [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) ![awesome-lint](https://github.com/sayhiben/awesome-rabbit-r1/actions/workflows/lint.yml/badge.svg)
A list of resources (and related projects) for hacking on the Rabbit r1

> [!WARNING]
> You may void your warranty or violate Rabbit's Terms of Service by using the software or following instructions on the pages linked to from this page. Do so at your own risk.

> [!NOTE]
> As of June 29, 2024, many of these projects are still in their infancy. The "r1_escape" jailbreak will help you get Android 13 running on your r1 for now. Please consider contributing to other listed projects.

## Contents

- [Jailbreaks](#jailbreaks)
- [Clients](#clients)
- [Servers](#servers)
- [Integrations & Utiliies](#integrations--utilities)
- [R1-Inspired Projects](#r1-inspired-projects)
- [Reference Material](#reference-material)
- [News & Articles](#news--articles)
    - [Jailbreaking](#news-jailbreaking)
    - [June 2024 Security Vulnerabilities](#news-june-2024-security-vulnerabilities)
- [Resources](#resources)

## Jailbreaks

- [r1_escape](https://github.com/RabbitHoleEscapeR1/r1_escape) - A jailbreak tool for the Rabbit r1.
- [Android on Rabbit r1](https://gist.github.com/veritas06/462844437bd8c5751b85d99c78c68fd8) - Instructions for using r1_escape to put Android on the r1.
- [retr0id's r1 jailbreak](https://retr0.id/stuff/r1_jailbreak/) - Web-based / web-usb jailbreak. WIP but testable, join rabbitude discord for support.

## Clients

- [rabbitude launcher](https://firmburrow.rabbitu.de/rabbitude/rabbitude-launcher) - A native Android project meant run on the r1 and reimplement the r1's frontend.
- [Rabbit R1 Launcher](https://github.com/Pinball3D/Rabbit-R1) - An effort to adapt the Rabbit R1 Launcher for use across any Android device.
- [r1 apk patcher](https://github.com/meowstercatel/r1-apk-patcher) - Tool to patch a clean rabbit apk into a working one.
- [r1 emulator](https://firmburrow.rabbitu.de/techblooded/emulator) - r1 emulator AVD Setup Files and Instructions.
- [Hop Project](https://firmburrow.rabbitu.de/crankyroo/MetaHop) - Project working to create a launcher and SDK for r1.

## Servers

- [rabbitude-backend](https://github.com/KibbeWater/rabbitude-backend) - A Go-based backend meant to reimplement the r1's backend and API endpoints.
- [rabbitserver-go](https://github.com/KibbeWater/rabbitserver-go) - A simple WebSocket wrapper for the RabbitHole API.
- [rabbitude-hole](https://github.com/KibbeWater/rabbitude-hole) - Rabbithole replacement for the rabbitude launcher.

## Integrations & Utilities

- [rabbithole-api](https://github.com/meowstercatel/rabbithole-api) - An API client for rabbit r1's rabbithole.
- [OTA Tool](https://firmburrow.rabbitu.de/emilyls/ota-tool) - A small utility for manually applying OTA updates to partition images.
- [LAMatHome](https://github.com/dot-Justin/LAMatHome) - A self-hosted integration suite that reads notes from the Rabbithole to add functionality to the r1.
- [Rabbit R1 IMEI Generator](https://github.com/annabelsandford/rabbit-r1-imeigen) - a JS-based tool designed to generate and validate IMEI numbers for Rabbit R1 devices ([Live Demo](https://annabelsandford.github.io/rabbit-r1-imeigen/imei_check_v1.html)).
- [Rabbitt Integration](https://github.com/GikitSRC/rabbitt_integration) - Use your r1's note saving feature to control things like Discord and the Rabbitt LAM.

## R1-Inspired Projects

- [Puppy](https://github.com/Antonoko/playdate-puppy-llm) - An LLM project using ChatGPT on the PlayDate using the r1's aesthetic.
- [KibbeWater/Rabbit](https://github.com/KibbeWater/Rabbit) - iOS App meant to emulate the Rabbit R1 software experience.
- [RabbitKit](https://github.com/KibbeWater/RabbitKit) - Communication Library for KibbeWater/Rabbit.
- [rabbit esp32](https://github.com/fbiego/rabbit-esp32) - A demo UI project for the WT32 SC01 Plus board inspired by Rabbit R1.
- [Rabbitt](https://github.com/GikitSRC/rabbitt) - A Small Action Model; named after Rabbit's Large Action Model that can take actions on websites on your behalf.
- [AgentOS](https://github.com/10cl/agentos) - An attempt to replicate r1's features natively on Android without the need for a remote backend.

## Reference Material

- [r1 api info](https://gist.github.com/DavidBuchanan314/aafce6ba7fc49b19206bd2ad357e47fa) - GitHub Gist with auth and endpoint details about the Rabbit API.
- [Unofficial r1 APK changelog](https://gist.github.com/DavidBuchanan314/b071223bdae43ec309d996f176992d7c) - A collection of unofficial Changelog notes for each APK released for the r1.
- [OTA API notes](https://gist.github.com/DavidBuchanan314/37ea2fb5ed15cc063eea82d8789b42b0) - Notes about the r1's OTA API.
- [MS35774 Info](https://github.com/CORN-R1/ms35774) - Stepper motor driver details for the ms35774 (r1's camera motor).
- [zShield Notes](https://gist.github.com/DavidBuchanan314/ceb3637b7a6877dd7f64950c84228043) - Notes about the obfuscation tool Rabbit uses to package their APKs.
- [GSI tree](https://github.com/RabbitHoleEscapeR1/device_rabbit_r1) - A view of the Rabbit r1's device image / filesystem.

## News & Articles

### News: Jailbreaking

- [XDA Forums: How to Unlock Rabbit R1 Bootloader - Tutorial](https://xdaforums.com/t/how-to-unlock-rabbit-r1-bootloader-tutorial.4676024/) - Article.
- [Yanko Design: Got a Rabbit R1? You can now run Android 13 on it and use it like a regular smartphone](https://www.yankodesign.com/2024/06/27/got-a-rabbit-r1-you-can-now-run-android-13-on-it-and-use-it-like-a-regular-smartphone/) - Article.

### News: July 2024

- [The Verge: The Rabbit R1 has been logging users' chats — with no way to wipe them](https://www.theverge.com/2024/7/12/24197073/rabbit-r1-user-chat-logs-security-issue-july-11th-update) - Article.

### News: June 2024 Security Vulnerabilities

- [Rabbitude: rabbit  data  breach: all r1 responses ever given can be downloaded](https://rabbitu.de/articles/security-disclosure-1) - Article.
- [Engadget: Rabbit R1 security issue allegedly leaves sensitive user data accessible to anybody](https://www.engadget.com/rabbit-r1-security-issue-allegedly-leaves-sensitive-user-data-accessible-to-anybody-120024215.html) - Article.
- [The Verge: A group of R1 jailbreakers found a massive security flaw in Rabbit's code](https://www.theverge.com/2024/6/26/24186614/rabbit-r1-security-flaw-api-key-codebase) - Article.
- [XDA: Major security flaw in Rabbit R1 code could have allowed hackers to access customer data, brick all devices](https://www.xda-developers.com/major-security-flaw-rabbit-r1-code-hackers-customer-data-brick-devices/) - Article.
- [Gizmodo: Hackers Claim They Have Access to a Hoard of Rabbit R1 User Data](https://gizmodo.com/rabbit-r1-hackers-can-brick-devices-1851561096) - Article.

## Resources

- [Rabbitude](https://rabbitu.de/) - A reverse-engineering and hacking project for the Rabbit r1.
- [Rabbitude Discord](https://discord.gg/BQ7VnDFysJ) - Rabbitude's Discord Server.
- [Rabbitude Firmburrow](https://firmburrow.rabbitu.de) - A self-hosted collection of Git repositories for Rabbitude's projects.
- [RabbitHoleEscapeR1](https://github.com/RabbitHoleEscapeR1) - A GitHub account that hosts several Rabbit r1 jailbreak-and-reverse-engineering-related resources.
- [DaveBuchanan314's Rabbit r1 Notes](https://gist.github.com/DavidBuchanan314/04bf8dace76f28f1e8a44155c5982641) - A GitHub Gist index of r1 notes.
