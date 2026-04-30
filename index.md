---
layout: default
title: Bitcoin Core App preview
permalink: /
classes: -home
---

# Bitcoin Core App preview

The Bitcoin Core App preview is ready for testing. These builds are unsigned CI artifacts, are intended for testing and feedback only, require a GitHub login to download, and should not be used with real funds.

## Download builds

- [macOS 14 preview build](https://github.com/johnny9/BitcoinCoreAppDevelopment/releases/download/latest/unsecure_macos-14_gui.zip){:target="_blank"} (`unsecure_macos-14_gui`)
- [Ubuntu 24.04 preview build](https://github.com/johnny9/BitcoinCoreAppDevelopment/releases/download/latest/unsecure_ubuntu-24.04_gui.zip){:target="_blank"} (`unsecure_ubuntu-24.04_gui`)

[Report feedback on GitHub Issues](https://github.com/bitcoin-core/gui-qml/issues){:target="_blank"}

## What to test

The current preview includes the core app experience documented on this site: first use, navigation, block status, wallet creation and import, activity, receiving, sending, settings, addresses, contacts, and console screens. We will continue refining the documentation as the preview release becomes more precise.

{% include picture.html
	image = "/assets/images/feedback-cover.png"
	retina = "/assets/images/feedback-cover@2x.png"
	big = "/assets/images/feedback-cover-big.png"
	alt-text = "Desktop and mobile screens showing the block status"
	width = 800
	height = 551
%}

{% include picture.html
	image = "/assets/images/onboarding-flow.png"
	retina = "/assets/images/onboarding-flow@2x.png"
	big = "/assets/images/onboarding-flow-big.png"
	alt-text = "All screens in the initial onboarding flow"
	width = 800
	height = 281
%}

## Download notes

- Log in to GitHub before opening a preview build link.
- Download the artifact for your operating system.
- Older Android devices may not allow you to install the application.
- If the application crashes on start, check whether a `bitcoin.conf` file exists and whether all settings it contains are correct.
- Pull requests may be set to signet while testing continues.
- To see the onboarding flow again, start the application with `--resetguisettings`.

### Apple Silicon macOS

If macOS sees the downloaded file as a document and not as an application, run this command in Terminal from the download folder:

	chmod +x ./bitcoin-qt

The artifact must also be locally signed before it can run:

	codesign -s - ./bitcoin-qt

Then right-click the file and select "Open". On newer macOS versions, you may also need to allow execution of the application in Privacy & Security settings ([more here](https://support.apple.com/en-us/102445#openanyway){:target="_blank"}).

## Feedback we need

When reporting feedback, include the operating system, device model, artifact name, what you tried to do, what happened, and screenshots or logs when available.

Useful questions:

- Did you install it on a phone, tablet, or desktop?
- Were the download instructions easy to understand?
- How was the installation process?
- How long did it take to sync?
- How did the installation affect the battery of your device?
- What do you think of the block status and wallet flows?
- How was the overall experience?

## Project links

- [Bitcoin Core website](https://bitcoincore.org){:target="_blank"}
- [Code repository](https://github.com/bitcoin-core/gui-qml){:target="_blank"}
- [Design repository](https://github.com/BitcoinDesign/Bitcoin-Core-App){:target="_blank"}
- [Project planning board](https://github.com/orgs/BitcoinDesign/projects/7){:target="_blank"}
- [Figma community file](https://www.figma.com/community/file/1185218794459295422){:target="_blank"}
