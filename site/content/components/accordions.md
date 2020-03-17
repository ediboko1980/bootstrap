---
layout: docs
title: Accordions
description: Use Rocket's accordion elements to segment content and show/hide when clicking on tabs
group: components
aliases:
  - "/components/"
toc: true
---

## Accordion

Use the `.accordion-panel-header` element and add the id of the targeted element to href, data-target and aria-controls attributes. The element that will be toggled is the `.collapse` from the following example:

{{< example >}}
<div class="accordion" id="accordionExample1">
    <div class="card card-sm card-body shadow-sm border-soft">
        <a href="#accordion-panel-1" data-target="#accordion-panel-1" class="accordion-panel-header"
            data-toggle="collapse" role="button" aria-expanded="false"
            aria-controls="accordion-panel-1">
            <span class="h6 mb-0 font-weight-bold">Our Company</span>
            <span class="icon"><i class="fas fa-plus"></i></span>
        </a>
        <div class="collapse" id="accordion-panel-1">
            <div class="pt-3">
                <p class="mb-0">
                    At Themesberg, our mission has always been focused
                    on bringing openness and
                    transparency to the design process. We've always
                    believed that by providing
                    a space where designers can share ongoing work not
                    only empowers them to
                    make better products, it also helps them grow.
                    We're proud to be a part of
                    creating a more open culture and to continue
                    building a product that
                    supports this vision.
                </p>
            </div>
        </div>
    </div>
    <div class="card card-sm card-body shadow-sm border-soft">
        <a href="#accordion-panel-2" data-target="#accordion-panel-2" class="accordion-panel-header"
            data-toggle="collapse" role="button" aria-expanded="false"
            aria-controls="accordion-panel-2">
            <span class="h6 mb-0 font-weight-bold">Pixel Components</span>
            <span class="icon"><i class="fas fa-plus"></i></span>
        </a>
        <div class="collapse" id="accordion-panel-2">
            <div class="pt-3">
                <p class="mb-0">
                    At Themesberg, our mission has always been focused
                    on bringing openness and
                    transparency to the design process. We've always
                    believed that by providing
                    a space where designers can share ongoing work not
                    only empowers them to
                    make better products, it also helps them grow.
                    We're proud to be a part of
                    creating a more open culture and to continue
                    building a product that
                    supports this vision. </p>
            </div>
        </div>
    </div>
    <div class="card card-sm card-body shadow-sm border-soft">
        <a href="#accordion-panel-3" data-target="#accordion-panel-3" class="accordion-panel-header"
            data-toggle="collapse" role="button" aria-expanded="false"
            aria-controls="accordion-panel-3">
            <span class="h6 mb-0 font-weight-bold">Licenses</span>
            <span class="icon"><i class="fas fa-plus"></i></span>
        </a>
        <div class="collapse" id="accordion-panel-3">
            <div class="pt-3">
                <p class="mb-0">
                    At Themesberg, our mission has always been focused
                    on bringing openness and
                    transparency to the design process. We've always
                    believed that by providing
                    a space where designers can share ongoing work not
                    only empowers them to
                    make better products, it also helps them grow.
                    We're proud to be a part of
                    creating a more open culture and to continue
                    building a product that
                    supports this vision. </p>
            </div>
        </div>
    </div>
</div>
{{< /example >}}

## Accordion with icons

The following example is an accordion with integrated icons:

{{< example >}}
<div class="accordion">
    <div class="card card-sm card-body shadow-sm border-soft">
        <a href="#panel-4" data-target="#panel-4" class="accordion-panel-header" data-toggle="collapse"
            role="button" aria-expanded="false" aria-controls="panel-4">
            <span class="icon-title h6 mb-0 font-weight-bold"><i class="fab fa-leanpub"></i>Our
                Company</span>
            <span class="icon"><i class="fas fa-plus"></i></span>
        </a>
        <div class="collapse" id="panel-4">
            <div class="pt-3">
                <p class="mb-0">
                    At Themesberg, our mission has always been focused on bringing openness and
                    transparency to the design process. We've always believed that by providing
                    a space where designers can share ongoing work not only empowers them to
                    make better products, it also helps them grow. We're proud to be a part of
                    creating a more open culture and to continue building a product that
                    supports this vision.
                </p>
            </div>
        </div>
    </div>
    <div class="card card-sm card-body shadow-sm border-soft">
        <a href="#panel-5" data-target="#panel-5" class="accordion-panel-header" data-toggle="collapse"
            role="button" aria-expanded="false" aria-controls="panel-5">
            <span class="icon-title h6 mb-0 font-weight-bold"><i class="fas fa-box-open"></i>Pixel
                Components</span>
            <span class="icon"><i class="fas fa-plus"></i></span>
        </a>
        <div class="collapse" id="panel-5">
            <div class="pt-3">
                <p class="mb-0">
                    At Themesberg, our mission has always been focused on bringing openness and
                    transparency to the design process. We've always believed that by providing
                    a space where designers can share ongoing work not only empowers them to
                    make better products, it also helps them grow. We're proud to be a part of
                    creating a more open culture and to continue building a product that
                    supports this vision. </p>
            </div>
        </div>
    </div>
    <div class="card card-sm card-body shadow-sm border-soft">
        <a href="#panel-6" data-target="#panel-6" class="accordion-panel-header" data-toggle="collapse"
            role="button" aria-expanded="false" aria-controls="panel-6">
            <span class="icon-title h6 mb-0 font-weight-bold"><i class="fas fa-donate"></i>Licenses</span>
            <span class="icon"><i class="fas fa-plus"></i></span>
        </a>
        <div class="collapse" id="panel-6">
            <div class="pt-3">
                <p class="mb-0">
                    At Themesberg, our mission has always been focused on bringing openness and
                    transparency to the design process. We've always believed that by providing
                    a space where designers can share ongoing work not only empowers them to
                    make better products, it also helps them grow. We're proud to be a part of
                    creating a more open culture and to continue building a product that
                    supports this vision. </p>
            </div>
        </div>
    </div>
</div>
{{< /example >}}