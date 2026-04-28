---
layout: default
title: Send
permalink: /send/
nav_order: 62
indent: true
---

# Sending bitcoin

**Status: Early design exploration**

_[Figma](https://www.figma.com/file/ek8w3n3upbluw5UL2lGhRx/Bitcoin-Core-App-Design?type=design&node-id=7516%3A13173&mode=design&t=sZSBHpOLLJmoMf57-1)_

The send flow covers creating, reviewing, signing, and broadcasting transactions for the current wallet experience.

Advanced signing and wallet types remain part of [future work]({{ '/future-work/' | relative_url }}).

Below is a visual map of the send-related screens and supporting flows.

{% include picture.html
	image = "/assets/images/feature-overview/1-7-send.png"
	retina = "/assets/images/feature-overview/1-7-send@2x.png"
	big = "/assets/images/feature-overview/1-7-send-big.png"
	alt-text = "A visual map of send-related screens"
	width = 800
	height = 409
%}

The complexity of the send flow can range dramatically. Some of the features to support:

- [Address book]({{ '/contacts/' | relative_url }})
- Fee estimation, recommendations and customization
- [Coin selection]({{ '/send/coin-selection/' | relative_url }})
- [External signers]({{ '/send/external-key/' | relative_url }})
- [Multiple signers]({{ '/send/multiple-keys/' | relative_url }})
- Multiple signing paths
- [Silent payments]({{ '/silent-payments/' | relative_url }})
- [Transaction batching]({{ '/send/multiple-recipients/' | relative_url }})
- [Transaction (PSBT) import and export]({{ '/send/import-export/' | relative_url }})
- Bitcoin URI scheme support
- Clipboard support

Screens and flows have not been fully designed yet. This page covers the current state.
