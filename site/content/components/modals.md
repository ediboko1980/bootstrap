---
layout: docs
title: Modals
description: Use Rockets's modals to develop faster and more interactive user interfaces
group: components
toc: true
---

## Modal example

The following example is a simple way of toggling a modal based on clicking on an element:

{{< example >}}
<button type="button" class="btn btn-secondary mb-3" data-toggle="modal" data-target="#modal-default">Toggle modal</button>
<div class="modal fade" id="modal-default" tabindex="-1" role="dialog" aria-labelledby="modal-default"
    aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered" role="document">
        <div class="modal-content">
            <div class="modal-header align-items-center">
                <h6 class="modal-title" id="modal-title-default">Terms of Service</h6> 
                <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                    <span aria-hidden="true">×</span>
                </button>
            </div>
            <div class="modal-body">
                <p>With less than a month to go before the European Union enacts new consumer privacy laws for its citizens, companies around the world are updating their terms of service agreements to comply.</p>
                <p>The European Union’s General Data Protection Regulation (G.D.P.R.) goes into effect on May 25 and is meant to ensure a common set of data rights in the European Union. It requires organizations to notify users as soon as possible of high-risk data breaches that could personally affect them.</p>  
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-secondary">I Got It</button>
            </div>
        </div>
    </div>
</div>
{{< /example >}}
