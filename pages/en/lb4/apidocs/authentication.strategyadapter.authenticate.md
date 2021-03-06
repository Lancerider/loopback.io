---
lang: en
title: 'API docs: authentication.strategyadapter.authenticate'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.authentication.strategyadapter.authenticate.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/authentication](./authentication.md) &gt; [StrategyAdapter](./authentication.strategyadapter.md) &gt; [authenticate](./authentication.strategyadapter.authenticate.md)

## StrategyAdapter.authenticate() method

The function to invoke the contained passport strategy. 1. Create an instance of the strategy 2. add success and failure state handlers 3. authenticate using the strategy

<b>Signature:</b>

```typescript
authenticate(request: Request): Promise<UserProfile>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  request | <code>Request</code> | The incoming request. |

<b>Returns:</b>

`Promise<UserProfile>`


