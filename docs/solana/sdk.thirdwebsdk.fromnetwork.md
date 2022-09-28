---
slug: /sdk.thirdwebsdk.fromnetwork
title: ThirdwebSDK.fromNetwork() method
hide_title: true
displayed_sidebar: solana
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## ThirdwebSDK.fromNetwork() method

Create a new SDK instance for the specified network

**Signature:**

```typescript
static fromNetwork(network: Network, storage?: ThirdwebStorage): ThirdwebSDK;
```

## Parameters

| Parameter | Type                        | Description                                                      |
| --------- | --------------------------- | ---------------------------------------------------------------- |
| network   | [Network](./sdk.network.md) | The network to connect to                                        |
| storage   | ThirdwebStorage             | <i>(Optional)</i> The storage provider to use or IPFS by default |

**Returns:**

[ThirdwebSDK](./sdk.thirdwebsdk.md)

an SDK instance