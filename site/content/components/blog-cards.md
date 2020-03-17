---
layout: docs
title: Blog cards
description: Documentation and examples for blog cards. Cards are built with as little markup and styles as possible, but still manage to deliver a ton of control and customization.
group: components
toc: true
---

## Blog card

Below is an example of a basic blog card with mixed content and a fixed width. Cards have no fixed width to start, so they’ll naturally fill the full width of its parent element. This is easily customized with Bootstrap 4 various sizing options

Use the `.shadow`, `.border` and `.bg-*` modifier classes to make blog cards more creative.

{{< example >}}
<div class="card bg-white border-light shadow-soft p-4 rounded">
    <a href="#">
        <img src="../../assets/img/blog/image-3.jpg" class="card-img-top" alt="">
    </a>
    <div class="card-body p-0 pt-4">
        <a href="#" class="h3">Apple Details Reveal Remarkable MacBook</a>
        <div class="d-flex align-items-center my-4">
            <img class="avatar avatar-sm rounded-circle" src="../../assets/img/team/profile-picture-6.jpg" alt=""> 
            <h6 class="text-muted small ml-2 mb-0">David L. Brown</h6>
        </div>
        <p class="mb-0">Following the release of the 16-inch MacBook Pro in late 2019, Apple was praised for the larger screen, the increased performance, and the improved keyboard.</p>
    </div>
</div>
{{< /example >}}
