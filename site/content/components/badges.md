---
layout: docs
title: Badges
description: Use Rocket's badges to add extra labeling to alongside titles or to cat
group: components
toc: true
---

## Badge

The following are the default badge styles from Rocket. Use the color variables to add preferred colors (ie. `badge-primary`, `badge-secondary`):

{{< example >}}
<h1>Example heading <span class="badge badge-primary">New</span></h1>
<h2>Example heading <span class="badge badge-secondary">New</span></h2>
<h3>Example heading <span class="badge badge-tertiary">New</span></h3>
<h4>Example heading <span class="badge badge-info">New</span></h4>
<h5>Example heading <span class="badge badge-danger">New</span></h5>
<h6>Example heading <span class="badge badge-warning">New</span></h6>
{{< /example >}}

## Badge as counter

You can also use the badges as a counter indicator in buttons or alongside text:

{{< example >}}
<button type="button" class="btn btn-primary">
    Messages <span class="badge badge-danger">9</span>
</button>
{{< /example >}}

## Badges as links

You can also use badges as links. For example you can use them to showcase categories:

{{< example >}}
<a href="#" class="badge badge-primary">Primary</a>
<a href="#" class="badge badge-secondary">Secondary</a>
<a href="#" class="badge badge-tertiary">Tertiary</a>
<a href="#" class="badge badge-success">Success</a>
<a href="#" class="badge badge-danger">Danger</a>
<a href="#" class="badge badge-warning">Warning</a>
<a href="#" class="badge badge-info">Info</a>
<a href="#" class="badge badge-light">Light</a>
<a href="#" class="badge badge-dark">Dark</a>
{{< /example >}}

## Sizing with badges

Fancy larger or smaller badges? Add `.badge-md` or `.badge-lg` for additional sizes.

{{< example >}}
<span class="badge badge-primary text-uppercase">Badge</span>
<span class="badge badge-md badge-primary text-uppercase">Badge md</span>
<span class="badge badge-lg badge-primary text-uppercase">Badge lg</span>
{{< /example >}}