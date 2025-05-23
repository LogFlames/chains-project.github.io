---
title: 3rd KTH Workshop on the Software Supply Chain 2024
---

<meta name="og:description" content="KTH hosts the 3rd CHAINS workshop where we have conversations about super cool research on software supply chain security and reliability. Check out our link to know more!">
<meta property="og:url" content="https://chains.proj.kth.se/software-supply-chain-workshop-3">
<meta property="og:image" content="https://avatars.githubusercontent.com/u/104410944?s=200&v=4">

# 3rd KTH Workshop on the Software Supply Chain
<p align="center">
    <img src="workshop_3_assets/website-group-picture.jpeg" alt="workshop cover image" width="1000px" />
</p>

Welcome to the 3rd KTH Workshop on the Software Supply Chain.
This workshop is organized in the context of the [CHAINS](https://chains.proj.kth.se/) research project.


* Location: [Salongen, Osquars backe 31, KTH Campus](https://www.kth.se/places/room/id/2ce773d5-3190-4588-8618-27ea2822000b)
* Date: April 26, 2024
* Time: 9h-17h

## Program

| Time | Event |
|------|-------|
| 0900 | Introduction by [Martin Monperrus](https://www.monperrus.net/martin/) |
| 0930 | Keynote: Understanding and Preventing Open-Source Software Supply Chain Attacks by [Piergiorgio Ladisa](https://scholar.google.com/citations?hl=it&user=LMHpRBkAAAAJ) ([slides](workshop_3_assets/slides/Keynote:%20Understanding%20and%20Preventing%20Open-Source%20Software%20Supply%20Chain%20Attacks.pdf)) |
| 1030 | Break + Poster Session (Elias + Master students) |
| 1120 | SBOM.exe: Runtime Integrity for Java by [Aman Sharma](https://algomaster99.github.io/) ([slides](https://algomaster99.github.io/talks/3rd-chains-workshop/slides.pdf)) |
| 1140 | SBOM2Sandbox: convenient sandboxing for Node.js by [Eric Cornelissen](https://ericcornelissen.dev/) ([slides](workshop_3_assets/slides/sbom2sandbox.pdf)) |
| 1200 | Lunch at [Syster o Bror](https://systerobror.se/) |
| 1400 | Applying consistent supply chain policies at scale with Minder and Trusty [Jakub Hrozek](https://www.linkedin.com/in/jhrozek/?originalSubdomain=se) ([slides](workshop_3_assets/slides/Supply%20Chain%20Security%20at%20Stacklok.pdf)) |
| 1450 | Maven-lockfile: Lockfiles for Maven by [Yogya Gamage](https://www.kth.se/profile/yogya) ([slides](workshop_3_assets/slides/Maven-lockfile.pdf))|
| 1500 | Fika |
| 1530 | Capslock: Capability Analysis in Golang ecosystem by [Carmine Cesarano](https://carminecesarano.github.io/) ([slides](workshop_3_assets/slides/Capslock:%20Capability%20Analysis%20in%20Golang%20ecosystem.pdf)) |
| 1550 | [BUMP: A Benchmark of Reproducible Breaking Dependency Updates](https://arxiv.org/abs/2401.09906) by [Frank Reyes-García](https://www.kth.se/profile/frankrg) ([slides](workshop_3_assets/slides/BUMP:%20A%20Benchmark%20of%20Reproducible%20Breaking%20Dependency%20Updates.pdf)) |
| 1610 | VEX-generation for containers by [Yekatierina Churakova](https://www.kth.se/profile/yekchu?l=en) ([slides](workshop_3_assets/slides/VEX-generation%20for%20containers.pdf)) |
| 1630 | Closing |

## Talks

### Understanding and Preventing Open-Source Software Supply Chain Attacks, [Piergiorgio Ladisa](https://scholar.google.com/citations?hl=it&user=LMHpRBkAAAAJ)), ING

<img src="workshop_3_assets/piergiorgio_ladisa.jpeg" alt="Piergiorgio Ladisa" width=100px />

Abstract: In this talk, we explore open-source supply chain attacks, aiming to understand and prevent them. We present a comprehensive, technology-agnostic taxonomy of these attacks and the mapping of existing safeguards that mitigate them. We also detail how third-party dependencies gain execution on downstream systems and suggest automated detection methods for malicious packages within open-source supply chain attacks. First, we present the evaluation of a machine learning-based approach for detecting malicious packages in JavaScript and Python. Then, we present the evaluation of a static approach to identify malicious packages in Java.

### Applying consistent supply chain policies at scale with Minder and Trusty, [Jakub Hrozek](https://www.linkedin.com/in/jhrozek/?originalSubdomain=se), Stacklok

<img src="workshop_3_assets/jakub_hrozek.jpeg" alt="Jakub Hrozek" width=100px />

Managing the security settings of a single repository can be done with a bit of scripting. But what do you do when your organisation has more repositories than developers and every developer team wants to apply their settings to meet their own definition of “secure”? In addition, how do you make sure that the dependencies your repositories are consuming are trustworthy and should be used as the foundation of your software?

In this talk, we’ll demonstrate two tools we have been developing at Stacklok - Minder which addresses the repository sprawl and allows users to secure their repositories by using an extensible policy engine and Trusty which allows to assess the quality of a software package by going beyond metrics like CVEs and instead focusing on how “trusted” a dependency can be.

## Poster session

List of posters:
* [Secured ( defined ) or Compliant ( declared ) SBOM](workshop_3_assets/posters/Secured%20(%20defined%20)%20or%20Compliant%20(%20declared%20)%20SBOM.pdf) by Hans Thorsen Lamm
* [Implementing SBOM Attestations in an Enterprise Context: An Exploration of the Benefits and Challenges](workshop_3_assets/posters/Implementing%20SBOM%20Attestations%20in%20an%20Enterprise%20Context:%20An%20Exploration%20of%20the%20Benefits%20and%20Challenges.pdf) by Christofer Vikström
* [Strengthening the Go Ethereum Supply Chain](workshop_3_assets/posters/Strengthening%20the%20Go%20Ethereum%20Supply%20Chain%20by%20Build%20Integrity.pdf) by Build Integrity by Vivi Andersson
* [Embedding the Software Supply Chain in Java Class Files](workshop_3_assets/posters/Embedding%20the%20Software%20Supply%20Chain%20in%20Java%20Class%20Files.pdf) by Daniel Williams
* [Analysis of the software supply chain of cryptocurrency wallets](workshop_3_assets/posters/Analysis%20of%20the%20software%20supply%20chain%20of%20cryptocurrency%20wallets.pdf) by Raphina Liu, Sofia Bobadilla
* [Fracturiser: Attack on Minecraft Mods](workshop_3_assets/posters/Fracturiser:%20Attack%20on%20Minecraft%20Mods.pdf) by Elias Lundell
* [An Evaluation of Air-gapped Software Builds](workshop_3_assets/posters/An%20Evaluation%20of%20Air-gapped%20Software%20Builds.pdf) by Oliver Schwalbe Lehtihet
* [Slowdown breaking dependency updates with Bumper](workshop_3_assets/posters/Slowdown%20breaking%20dependency%20updates%20with%20Bumper.pdf) by Federico Bono

## Sponsors

<div style="display: flex; justify-content: center;">
<img src="workshop_3_assets/ssf_logo.svg" alt="Imagen 2" style="width: 200; margin: auto;"/>
  <img src="workshop_3_assets/df_logo.png" alt="Imagen 1" style="max-width: 30%; margin: auto;"/> 
</div>

## Previous editions

- [2nd KTH Workshop on the Software Supply Chain](/software-supply-chain-workshop-2.md)
- [1st KTH Workshop on the Software Supply Chain](/software-suppply-chain-workshop-1.md)
