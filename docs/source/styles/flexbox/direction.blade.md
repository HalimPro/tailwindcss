---
extends: _layouts.markdown
title: "Flexbox"
---

<div class="font-semibold text-slate-light text-base uppercase tracking-wide mb-2">Flexbox</div>

# Flex Direction

<div class="subnav">
    <a class="subnav-link" href="#usage">Usage</a>
    <a class="subnav-link" href="#responsive">Responsive</a>
    <a class="subnav-link" href="#customizing">Customizing</a>
</div>

Tailwind provides a comprehensive set of Flexbox utilities out of the box to make it easy for you to implement complex layouts without having to write any new CSS.

<h2>Row <span class="ml-2 font-semibold text-slate-light text-sm uppercase tracking-wide">Default</span></h2>

Use `.flex-row` to position flex items horizontally in the same direction as text:

@component('_partials.code-sample')
<div class="flex flex-row bg-smoke-light">
    <div class="text-slate text-center bg-smoke px-4 py-2 m-2">1</div>
    <div class="text-slate text-center bg-smoke px-4 py-2 m-2">2</div>
    <div class="text-slate text-center bg-smoke px-4 py-2 m-2">3</div>
</div>
@endcomponent

## Row reversed

Use `.flex-row-reverse` to position flex items horizontally in the opposite direction:

@component('_partials.code-sample')
<div class="flex flex-row-reverse bg-smoke-light">
    <div class="text-slate text-center bg-smoke px-4 py-2 m-2">1</div>
    <div class="text-slate text-center bg-smoke px-4 py-2 m-2">2</div>
    <div class="text-slate text-center bg-smoke px-4 py-2 m-2">3</div>
</div>
@endcomponent

## Column

Use `.flex-col` to position flex items vertically:

@component('_partials.code-sample')
<div class="flex flex-col bg-smoke-light">
    <div class="text-slate text-center bg-smoke px-4 py-2 m-2">1</div>
    <div class="text-slate text-center bg-smoke px-4 py-2 m-2">2</div>
    <div class="text-slate text-center bg-smoke px-4 py-2 m-2">3</div>
</div>
@endcomponent

## Column reversed

Use `.flex-col-reverse` to position flex items vertically in the opposite direction:

@component('_partials.code-sample')
<div class="flex flex-col-reverse bg-smoke-light">
    <div class="text-slate text-center bg-smoke px-4 py-2 m-2">1</div>
    <div class="text-slate text-center bg-smoke px-4 py-2 m-2">2</div>
    <div class="text-slate text-center bg-smoke px-4 py-2 m-2">3</div>
</div>
@endcomponent