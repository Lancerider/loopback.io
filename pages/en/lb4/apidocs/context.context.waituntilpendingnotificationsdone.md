---
lang: en
title: 'API docs: context.context.waituntilpendingnotificationsdone'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.context.context.waituntilpendingnotificationsdone.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [Context](./context.context.md) &gt; [waitUntilPendingNotificationsDone](./context.context.waituntilpendingnotificationsdone.md)

## Context.waitUntilPendingNotificationsDone() method

Wait until observers are notified for all of currently pending notification events.

This method is for test only to perform assertions after observers are notified for relevant events.

<b>Signature:</b>

```typescript
protected waitUntilPendingNotificationsDone(timeout?: number): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  timeout | <code>number</code> |  |

<b>Returns:</b>

`Promise<void>`


