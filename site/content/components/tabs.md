---
layout: docs
title: Tabs
description: Use Rockets's tabs to partition important data into easily navigable and interchangeable elements
group: components
toc: true
---

## Tab example

{{< example >}}
<div class="row">
    <div class="col-12">
        <nav>
            <div class="nav nav-tabs flex-column flex-md-row bg-white shadow-soft border border-light justify-content-around rounded mb-lg-3 py-3" id="nav-tab" role="tablist">
                <a class="nav-item nav-link rounded mr-md-3 active" id="nav-content-research-tab" data-toggle="tab" href="#nav-content-research" role="tab" aria-controls="nav-content-research" aria-selected="true"><span class="d-block"><i class="fas fa-file-alt"></i><span class="font-weight-normal">Content Research</span></span></a>
                <a class="nav-item nav-link rounded mr-md-3" id="nav-rank-track-tab" data-toggle="tab" href="#nav-rank-track" role="tab" aria-controls="nav-rank-track" aria-selected="false"><i class="fas fa-chart-line"></i><span class="font-weight-normal">Rank Tracking</span></a>
                <a class="nav-item nav-link rounded mr-md-3" id="nav-web-monitor-tab" data-toggle="tab" href="#nav-web-monitor" role="tab" aria-controls="nav-web-monitor" aria-selected="false"><i class="far fa-bell"></i><span class="font-weight-normal">Web Monitoring</span></a>
            </div>
        </nav>
        <div class="tab-content mt-4" id="nav-tabContent">
            <div class="tab-pane fade show active" id="nav-content-research" role="tabpanel" aria-labelledby="nav-content-research-tab">
                <p>Content Research</p>
            </div>
            <div class="tab-pane fade" id="nav-rank-track" role="tabpanel" aria-labelledby="nav-rank-track-tab">
                <p>Rank Tracking</p>
            </div>
            <div class="tab-pane fade" id="nav-web-monitor" role="tabpanel" aria-labelledby="nav-web-monitor-tab">
                <p>Web Monitoring</p>
            </div>
        </div>
    </div>
</div>
{{< /example >}}
