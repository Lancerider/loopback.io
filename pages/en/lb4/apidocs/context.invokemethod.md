---
lang: en
title: 'API docs: context.invokemethod'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.context.invokemethod.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [invokeMethod](./context.invokemethod.md)

## invokeMethod() function

Invoke an instance method with dependency injection

<b>Signature:</b>

```typescript
export declare function invokeMethod(target: object, method: string, ctx: Context, nonInjectedArgs?: any[]): ValueOrPromise<BoundValue>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  target | <code>object</code> | Target of the method, it will be the class for a static method, and instance or class prototype for a prototype method |
|  method | <code>string</code> | Name of the method |
|  ctx | <code>Context</code> | Context |
|  nonInjectedArgs | <code>any[]</code> | Optional array of args for non-injected parameters |

<b>Returns:</b>

`ValueOrPromise<BoundValue>`


