---
lang: en
title: 'API docs: service-proxy.servicemixin'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.service-proxy.servicemixin.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/service-proxy](./service-proxy.md) &gt; [ServiceMixin](./service-proxy.servicemixin.md)

## ServiceMixin() function

A mixin class for Application that creates a .serviceProvider() function to register a service automatically. Also overrides component function to allow it to register repositories automatically.

<b>Signature:</b>

```typescript
export declare function ServiceMixin<T extends Class<any>>(superClass: T): {
    new (...args: any[]): {
        [x: string]: any;
        serviceProvider<S>(provider: Class<Provider<S>>, name?: string | undefined): Binding<S>;
        component(component: Class<unknown>, name?: string | undefined): void;
        mountComponentServices(component: Class<unknown>): void;
    };
} & T;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  superClass | <code>T</code> |  |

<b>Returns:</b>

`{
    new (...args: any[]): {
        [x: string]: any;
        serviceProvider<S>(provider: Class<Provider<S>>, name?: string | undefined): Binding<S>;
        component(component: Class<unknown>, name?: string | undefined): void;
        mountComponentServices(component: Class<unknown>): void;
    };
} & T`

## Example


```ts
class MyApplication extends ServiceMixin(Application) {}

```
Please note: the members in the mixin function are documented in a dummy class called <a href="#ServiceMixinDoc">ServiceMixinDoc</a>


