---
layout: docs
title: Alerts
description: Use alerts to provide contextual feedback to your users based on their input and behaviour
group: components
aliases:
  - "/components/"
toc: true
---

## Alerts

Alerts can be used to show your users error, success, informational or warning messages. Use the color variables such as `alert-primary` or `alert-secondary` to add your preferred colors:

{{< example >}}
<div class="alert alert-primary" role="alert">
    <span class="alert-inner--text">This is a primary  alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.</span>
</div>
<div class="alert alert-secondary" role="alert">
    <span class="alert-inner--text">This is a secondary alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.</span>
</div>
<div class="alert alert-success" role="alert">
    <span class="alert-inner--text">This is a success alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.</span>
</div>
<div class="alert alert-info" role="alert">
    <span class="alert-inner--text">This is a info alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.</span>
</div>
<div class="alert alert-warning" role="alert">
    <span class="alert-inner--text">This is a warning alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.</span>
</div>
<div class="alert alert-danger" role="alert">
    <span class="alert-inner--text">This is a danger alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.</span>
</div>
{{< /example >}}

## Alerts with icons

The following alerts are coupled with descriptive icons:

{{< example >}}
<div class="alert alert-primary alert-dismissible fade show" role="alert">
    <span class="alert-inner--icon"><i class="fas fa-brain"></i></span>
    <span class="alert-inner--text"><strong>Primary alert!</strong> You successfully read this important alert message.</span>
    <button type="button" class="close" data-dismiss="alert" aria-label="Close">
        <span aria-hidden="true">&times;</span>
    </button>
</div>
<div class="alert alert-secondary alert-dismissible fade show" role="alert">
    <span class="alert-inner--icon"><i class="far fa-dizzy"></i></span>
    <span class="alert-inner--text"><strong>Secondary note!</strong> You successfully read this important alert message.</span>
    <button type="button" class="close" data-dismiss="alert" aria-label="Close">
        <span aria-hidden="true">&times;</span>
    </button>
</div>
<div class="alert alert-success alert-dismissible fade show" role="alert">
    <span class="alert-inner--icon"><i class="far fa-thumbs-up"></i></span>
    <span class="alert-inner--text"><strong>Well done!</strong> You successfully read this important alert message.</span>
    <button type="button" class="close" data-dismiss="alert" aria-label="Close">
        <span aria-hidden="true">&times;</span>
    </button>
</div>
<div class="alert alert-info alert-dismissible fade show" role="alert">
    <span class="alert-inner--icon"><i class="far fa-bell"></i></span>
    <span class="alert-inner--text"><strong>Heads up!</strong>This alert needs your attention, but it's not super important.</span>
    <button type="button" class="close" data-dismiss="alert" aria-label="Close">
        <span aria-hidden="true">&times;</span>
    </button>
</div>
<div class="alert alert-warning alert-dismissible fade show" role="alert">
    <span class="alert-inner--icon"><i class="fas fa-exclamation-circle"></i></span>
    <span class="alert-inner--text"><strong>Warning!</strong> Better check yourself, you're not looking too good.</span>
    <button type="button" class="close" data-dismiss="alert" aria-label="Close">
        <span aria-hidden="true">&times;</span>
    </button>
</div>
<div class="alert alert-danger alert-dismissible fade show" role="alert">
    <span class="alert-inner--icon"><i class="fas fa-fire"></i></span>
    <span class="alert-inner--text"><strong>Oh snap!</strong> Change a few things up and try submitting again.</span>
    <button type="button" class="close" data-dismiss="alert" aria-label="Close">
        <span aria-hidden="true">&times;</span>
    </button>
</div>
{{< /example >}}

## Alerts with extra content

The following alerts are useful when you want to give more information and context to your users:

{{< example >}}
<div class="alert alert-primary" role="alert">
    <span class="alert-inner--icon"><i class="far fa-dizzy"></i></span>
    <h5 class="alert-heading">Secondary Info!</h5>
    <p>Aww yeah, you successfully read this important alert message. This example text is going to run a bit longer so that you can see how spacing within an alert works with this kind of content.</p>
    <hr>
    <p class="mb-0">Whenever you need to, be sure to use margin utilities to keep things nice and tidy.</p>
</div>
<div class="alert alert-secondary" role="alert">
    <span class="alert-inner--icon"><i class="far fa-thumbs-up"></i></span>
    <h5 class="alert-heading">Well done!</h5>
    <p>Aww yeah, you successfully read this important alert message. This example text is going to run a bit longer so that you can see how spacing within an alert works with this kind of content.</p>
    <hr>
    <p class="mb-0">Whenever you need to, be sure to use margin utilities to keep things nice and tidy.</p>
</div>
<div class="alert alert-info" role="alert">
    <span class="alert-inner--icon"><i class="far fa-bell"></i></span>
    <h5 class="alert-heading">Heads up!</h5>
    <p>Aww yeah, you successfully read this important alert message. This example text is going to run a bit longer so that you can see how spacing within an alert works with this kind of content.</p>
    <hr>
    <p class="mb-0">Whenever you need to, be sure to use margin utilities to keep things nice and tidy.</p>
</div>
<div class="alert alert-warning" role="alert">
    <span class="alert-inner--icon"><i class="fas fa-exclamation-circle"></i></span>
    <h5 class="alert-heading">Warning!</h5>
    <p>Aww yeah, you successfully read this important alert message. This example text is going to run a bit longer so that you can see how spacing within an alert works with this kind of content.</p>
    <hr>
    <p class="mb-0">Whenever you need to, be sure to use margin utilities to keep things nice and tidy.</p>
</div>
<div class="alert alert-danger" role="alert">
    <span class="alert-inner--icon"><i class="fas fa-fire"></i></span>
    <h5 class="alert-heading">Danger!</h5>
    <p>Aww yeah, you successfully read this important alert message. This example text is going to run a bit longer so that you can see how spacing within an alert works with this kind of content.</p>
    <hr>
    <p class="mb-0">Whenever you need to, be sure to use margin utilities to keep things nice and tidy.</p>
</div>
{{< /example >}}
