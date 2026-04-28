---
layout: default
title: Current feature set
permalink: /features/
nav_order: 10
---

# Current feature set

This page summarizes the app behavior documented for the current unsigned preview. Completion status is intentionally approximate while the preview release is being prepared, and the documentation will be tightened as testing feedback comes in.

The goal is broad parity with the existing Qt application while improving the structure of common node and wallet workflows. Some options are intentionally organized differently in this app.

### General

| Feature                                                    | App     | Qt      |
| ---------------------------------------------------------- | ------- | ------- |
| Android support                                            | ✓       | ✗       |
| [Guided setup experience]({{ '/first-use/' | relative_url }}) | ✓       | ✗       |
| Message signing & verification                             | ✓       | ✓       |

### Wallet management

| Feature                                                    | App     | Qt      |
| ---------------------------------------------------------- | ------- | ------- |
| Wallet switching                                           | ✓       | ✓       |
| [Activity]({{ '/activity/' | relative_url }})              | ✓       | ✓       |
| [Create single-key wallets]({{ '/wallet/create/' | relative_url }}) | ✓       | ✓       |
| Create multi-key wallets                                   | Future  | ✗       |
| Descriptor wallets                                         | ✓       | ✓       |
| Watch-only wallets                                         | ✓       | ✓       |
| Wallet file backup                                         | ✓       | ✓       |
| [Wallet file import]({{ '/wallet/import/' | relative_url }}) | ✓       | ✓       |
| Password protection                                        | ✓       | ✓       |

### [Sending]({{ '/send/' | relative_url }})

| Feature                                                    | App     | Qt      |
| ---------------------------------------------------------- | ------- | ------- |
| Transaction creation & broadcast                           | ✓       | ✓       |
| "Send all" option                                          | ✓       | ✓       |
| Legacy address support                                     | ✓       | ✓       |
| Recommended fee rate                                       | ✓       | ✓       |
| Priority-based fee options                                 | ✓       | ✗       |
| Manual fee rate selection                                  | ✓       | ✓       |
| Multiple recipients                                        | ✓       | ✓       |
| Coin selection                                             | ✓       | ✓       |
| Contacts                                                   | ✓       | ✓       |
| Input & output visualization                               | ✓       | ✗       |
| PSBT import & export                                       | ✓       | ✓       |
| Import via clipboard                                       | ✓       | ✓       |
| Import via BIP-21 URI                                      | ✓       | ✓       |
| Replace-by-fee                                             | ✓       | ✓       |
| Include fee in amount                                      | ✓       | ✓       |
| Single-key transaction signing                             | ✓       | ✓       |
| External signer support via HWI                            | ✓       | ✓       |
| Time locks                                                 | ✓       | ✗       |

### [Receiving]({{ '/receive/' | relative_url }})

| Feature                                                    | App     | Qt      |
| ---------------------------------------------------------- | ------- | ------- |
| Address generation                                         | ✓       | ✓       |
| List of generated wallet addresses                         | ✓       | ✓       |
| Address labeling                                           | ✓       | ✓       |
| Address type selection                                     | ✓       | ✓       |
| Payment request message                                    | ✓       | ✓       |
| Share via QR code                                          | ✓       | ✓       |
| Share via BIP-21 URI                                       | ✓       | ✓       |
| Reusable addresses (Silent Payments)                       | Future  | ✗       |

### Node management

| Feature                                                                         | App     | Qt      |
| ------------------------------------------------------------------------------- | ------- | ------- |
| [Block synchronization status]({{ '/block-status/' | relative_url }})            | ✓       | ✓       |
| [Pruning]({{ '/settings/storage/' | relative_url }})                            | ✓       | ✓       |
| [Snapshot creation & import]({{ '/snapshot/' | relative_url }}) (assumeUTXO)    | Future  | ✗       |
| [Network settings]({{ '/settings/network/' | relative_url }})                   | ✓       | ✓       |
| Test networks                                                                   | ✓       | ✓       |
| [Peers screen]({{ '/settings/peers/' | relative_url }})                         | ✓       | ✓       |

### Settings

The structure of the settings has changed quite a bit. Almost all settings are still available, but have been moved to different screens, typically to be available contextually. You can find a more detailed mapping in [this Google Sheet](https://docs.google.com/spreadsheets/d/1JyJDZBR-jyfXJgriTNiybVA1X4r0aK0Pc3D1LfVv_MA/edit?usp=sharing){:target="_blank"}.

| Feature                                                              | App     | Qt      |
| -------------------------------------------------------------------- | ------- | ------- |
| [About screen]({{ '/settings/about/' | relative_url }})              | ✓       | ✓       |
| [Display settings]({{ '/settings/display/' | relative_url }})        | ✓       | ✓       |
| [Developer settings]({{ '/settings/developer/' | relative_url }})    | ✓       | ✗       |
| [Console screen]({{ '/console/' | relative_url }})                   | ✓       | ✓       |
| bitcoin.conf access                                                  | ✓       | ✓       |

See [future work]({{ '/future-work/' | relative_url }}) for documented ideas that are not treated as part of the current preview.
