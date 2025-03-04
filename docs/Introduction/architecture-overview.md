---
layout: nodes.liquid
section: smartContract
date: Last Modified
title: "Architecture Overview"
permalink: "docs/architecture-overview/"
whatsnext: {"Basic Request Model":"/docs/architecture-request-model/", "Decentralized Data Model":"/docs/architecture-decentralized-model/", "Off-Chain Reporting":"/docs/off-chain-reporting/"}
hidden: false
metadata: 
  title: "Chainlink Architecture Overview"
  image: 
    0: "/files/OpenGraph_V3.png"
    1: "670379d-OpenGraph_V3.png"
    2: 1459
    3: 1459
    4: "#dbe1f8"
---
[block:image]
{
  "images": [
    {
      "image": [
        "/files/8c35025-Request__Receive_Data.png",
        "5c0ae00-8c35025-Request__Receive_Data.png",
        3246,
        730,
        "#f1f4fb"
      ]
    }
  ]
}
[/block]
# Basic Request Model

Chainlink connects smart contracts with external data using its decentralized oracle network. Chainlink API requests are handled 1:1 by an oracle.

The [Basic Request Model](../architecture-request-model/) describes the on-chain architecture of requesting data from a single oracle source.

To learn how to make a GET request using a single oracle, see [Make a GET Request](../make-a-http-get-request/).

# Decentralized Data Model

For a more robust and trustworthy answer, you can aggregate data from many oracles. With on-chain aggregation, data is aggregated from a decentralized network of independent oracle nodes. This architecture is applied to Chainlink Price Feeds, which aggregate asset price data.

The [Decentralized Data Model](../architecture-decentralized-model/) describes how data is aggregated, and how consumer contracts can retrieve this data.

To learn how to consume the price of ETH in your smart contract, see [Get the Latest Price](../get-the-latest-price/).