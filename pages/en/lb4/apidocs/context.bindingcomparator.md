---
lang: en
title: 'API docs: context.bindingcomparator'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.context.bindingcomparator.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [BindingComparator](./context.bindingcomparator.md)

## BindingComparator interface

Compare function to sort an array of bindings. It is used by `Array.prototype.sort()`<!-- -->.

<b>Signature:</b>

```typescript
export interface BindingComparator 
```

## Example


```ts
const compareByKey: BindingComparator = (a, b) => a.key.localeCompare(b.key);

```


