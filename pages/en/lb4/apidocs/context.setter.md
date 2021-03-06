---
lang: en
title: 'API docs: context.setter'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.context.setter.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [Setter](./context.setter.md)

## Setter type

The function injected by `@inject.setter(bindingKey)`<!-- -->. It sets the underlying binding to a constant value using `binding.to(value)`<!-- -->.

<b>Signature:</b>

```typescript
export declare type Setter<T> = (value: T) => void;
```

## Example


```ts
setterFn('my-value');

```


