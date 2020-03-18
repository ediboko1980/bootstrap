---
layout: docs
title: Navigation bars
description: Use Rockets's navigation bar to add menu items, dropdown items and provide users a good way to navigate your website
group: components
toc: true
---

## Navbar example

The following navigation bar is a basic example from what is used in Rocket:

{{< example >}}
<nav class="navbar navbar-expand-lg navbar-transparent navbar-dark navbar-theme-primary mb-4">
    <div class="container position-relative">
        <a class="navbar-brand mr-lg-3" href="#">
            <img class="navbar-brand-dark" src="../../assets/brand/rocket.svg" alt="menuimage">
            <img class="navbar-brand-light" src="../../assets/brand/rocket-dark.svg" alt="menuimage">
        </a>
        <div class="navbar-collapse collapse" id="navbar-default-primary">
            <div class="navbar-collapse-header">
                <div class="row">
                    <div class="col-6 collapse-brand">
                        <a href="#">
                            <img src="../../assets/img/brand/rocket-dark.svg" alt="menuimage">
                        </a>
                    </div>
                    <div class="col-6 collapse-close">
                        <i class="fas fa-times" data-toggle="collapse" role="button"
                            data-target="#navbar-default-primary" aria-controls="navbar-default-primary"
                            aria-expanded="false" aria-label="Toggle navigation"></i>
                    </div>
                </div>
            </div>
            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                <li class="nav-item">
                    <a href="#" class="nav-link">About</a>
                </li>
                <li class="nav-item dropdown">
                    <a href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="fas fa-angle-down nav-link-arrow"></i>
                        <span class="nav-link-inner-text">Dropdown 2 </span>
                    </a>
                    <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">Dropdown item 1</a></li>
                        <li><a class="dropdown-item" href="#">Dropdown item 2</a></li>
                        <li class="dropdown-submenu">
                            <a href="#" class="dropdown-toggle dropdown-item d-flex justify-content-between align-items-center" aria-haspopup="true" aria-expanded="false">Dropdown item 3 <i class="fas fa-angle-right nav-link-arrow"></i></a>
                            <ul class="dropdown-menu">
                                <li>
                                    <a href="#" class="dropdown-item">Submenu item 1</a>
                                </li>
                                <li>
                                    <a href="#" class="dropdown-item">Submenu item 2</a>
                                </li>
                            </ul>
                        </li>
                        <li><a class="dropdown-item" href="#">Dropdown item 4</a></li>
                    </ul>
                </li>
            </ul>
        </div>
        <div class="d-flex align-items-center">
            <p class="text-white mb-0">Primary navbar</p>
            <button class="navbar-toggler ml-2" type="button" data-toggle="collapse"
                data-target="#navbar-default-primary" aria-controls="navbar-default-primary"
                aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
        </div>
    </div>
</nav>
{{< /example >}}

## Navbar colors

We've made sure that you can change the colors of the navbar very easily. All you have to do is add the modifier class .navbar-theme-* (eg. `.navbar-theme-primary`, `.navbar-theme-secondary`, `.navbar-theme-dark`) in order to change the colors. As you can see, even the dropdown item hover effect will change their color.

{{< example >}}
<nav class="navbar navbar-expand-lg navbar-transparent navbar-dark navbar-theme-secondary mb-4">
    <div class="container position-relative">
        <a class="navbar-brand mr-lg-3" href="#">
            <img class="navbar-brand-dark" src="../../assets/brand/rocket.svg" alt="menuimage">
            <img class="navbar-brand-light" src="../../assets/brand/rocket-dark.svg" alt="menuimage">
        </a>
        <div class="navbar-collapse collapse" id="navbar-default-primary">
            <div class="navbar-collapse-header">
                <div class="row">
                    <div class="col-6 collapse-brand">
                        <a href="#">
                            <img src="../../assets/img/brand/rocket-dark.svg" alt="menuimage">
                        </a>
                    </div>
                    <div class="col-6 collapse-close">
                        <i class="fas fa-times" data-toggle="collapse" role="button"
                            data-target="#navbar-default-primary" aria-controls="navbar-default-primary"
                            aria-expanded="false" aria-label="Toggle navigation"></i>
                    </div>
                </div>
            </div>
            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                <li class="nav-item">
                    <a href="#" class="nav-link">About</a>
                </li>
                <li class="nav-item dropdown">
                    <a href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="fas fa-angle-down nav-link-arrow"></i>
                        <span class="nav-link-inner-text">Dropdown 2 </span>
                    </a>
                    <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">Dropdown item 1</a></li>
                        <li><a class="dropdown-item" href="#">Dropdown item 2</a></li>
                        <li class="dropdown-submenu">
                            <a href="#" class="dropdown-toggle dropdown-item d-flex justify-content-between align-items-center" aria-haspopup="true" aria-expanded="false">Dropdown item 3 <i class="fas fa-angle-right nav-link-arrow"></i></a>
                            <ul class="dropdown-menu">
                                <li>
                                    <a href="#" class="dropdown-item">Submenu item 1</a>
                                </li>
                                <li>
                                    <a href="#" class="dropdown-item">Submenu item 2</a>
                                </li>
                            </ul>
                        </li>
                        <li><a class="dropdown-item" href="#">Dropdown item 4</a></li>
                    </ul>
                </li>
            </ul>
        </div>
        <div class="d-flex align-items-center">
            <p class="text-white mb-0">Secondary navbar</p>
            <button class="navbar-toggler ml-2" type="button" data-toggle="collapse"
                data-target="#navbar-default-primary" aria-controls="navbar-default-primary"
                aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
        </div>
    </div>
</nav>
<nav class="navbar navbar-expand-lg navbar-transparent navbar-dark navbar-theme-dark mb-4">
    <div class="container position-relative">
        <a class="navbar-brand mr-lg-3" href="#">
            <img class="navbar-brand-dark" src="../../assets/brand/rocket.svg" alt="menuimage">
            <img class="navbar-brand-light" src="../../assets/brand/rocket-dark.svg" alt="menuimage">
        </a>
        <div class="navbar-collapse collapse" id="navbar-default-primary">
            <div class="navbar-collapse-header">
                <div class="row">
                    <div class="col-6 collapse-brand">
                        <a href="#">
                            <img src="../../assets/img/brand/rocket-dark.svg" alt="menuimage">
                        </a>
                    </div>
                    <div class="col-6 collapse-close">
                        <i class="fas fa-times" data-toggle="collapse" role="button"
                            data-target="#navbar-default-primary" aria-controls="navbar-default-primary"
                            aria-expanded="false" aria-label="Toggle navigation"></i>
                    </div>
                </div>
            </div>
            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                <li class="nav-item">
                    <a href="#" class="nav-link">About</a>
                </li>
                <li class="nav-item dropdown">
                    <a href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="fas fa-angle-down nav-link-arrow"></i>
                        <span class="nav-link-inner-text">Dropdown 2 </span>
                    </a>
                    <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">Dropdown item 1</a></li>
                        <li><a class="dropdown-item" href="#">Dropdown item 2</a></li>
                        <li class="dropdown-submenu">
                            <a href="#" class="dropdown-toggle dropdown-item d-flex justify-content-between align-items-center" aria-haspopup="true" aria-expanded="false">Dropdown item 3 <i class="fas fa-angle-right nav-link-arrow"></i></a>
                            <ul class="dropdown-menu">
                                <li>
                                    <a href="#" class="dropdown-item">Submenu item 1</a>
                                </li>
                                <li>
                                    <a href="#" class="dropdown-item">Submenu item 2</a>
                                </li>
                            </ul>
                        </li>
                        <li><a class="dropdown-item" href="#">Dropdown item 4</a></li>
                    </ul>
                </li>
            </ul>
        </div>
        <div class="d-flex align-items-center">
            <p class="text-white mb-0">Dark navbar</p>
            <button class="navbar-toggler ml-2" type="button" data-toggle="collapse"
                data-target="#navbar-default-primary" aria-controls="navbar-default-primary"
                aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
        </div>
    </div>
</nav>
{{< /example >}}

## Navbar text colors

Using `.navbar-dark` will make the content within the navbar white while `.navbar-light` will make the content and menu items dark. We made sure the logo also changes based on the `.navbar-brand-dark` and `.navbar-brand-light` identifier classes

{{< example >}}
<nav class="navbar navbar-expand-lg navbar-transparent navbar-dark navbar-theme-secondary mb-4">
    <div class="container position-relative">
        <a class="navbar-brand mr-lg-3" href="#">
            <img class="navbar-brand-dark" src="../../assets/brand/rocket.svg" alt="menuimage">
            <img class="navbar-brand-light" src="../../assets/brand/rocket-dark.svg" alt="menuimage">
        </a>
        <div class="navbar-collapse collapse" id="navbar-default-primary">
            <div class="navbar-collapse-header">
                <div class="row">
                    <div class="col-6 collapse-brand">
                        <a href="#">
                            <img src="../../assets/img/brand/rocket-dark.svg" alt="menuimage">
                        </a>
                    </div>
                    <div class="col-6 collapse-close">
                        <i class="fas fa-times" data-toggle="collapse" role="button"
                            data-target="#navbar-default-primary" aria-controls="navbar-default-primary"
                            aria-expanded="false" aria-label="Toggle navigation"></i>
                    </div>
                </div>
            </div>
            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                <li class="nav-item">
                    <a href="#" class="nav-link">About</a>
                </li>
                <li class="nav-item dropdown">
                    <a href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="fas fa-angle-down nav-link-arrow"></i>
                        <span class="nav-link-inner-text">Dropdown 2 </span>
                    </a>
                    <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">Dropdown item 1</a></li>
                        <li><a class="dropdown-item" href="#">Dropdown item 2</a></li>
                        <li class="dropdown-submenu">
                            <a href="#" class="dropdown-toggle dropdown-item d-flex justify-content-between align-items-center" aria-haspopup="true" aria-expanded="false">Dropdown item 3 <i class="fas fa-angle-right nav-link-arrow"></i></a>
                            <ul class="dropdown-menu">
                                <li>
                                    <a href="#" class="dropdown-item">Submenu item 1</a>
                                </li>
                                <li>
                                    <a href="#" class="dropdown-item">Submenu item 2</a>
                                </li>
                            </ul>
                        </li>
                        <li><a class="dropdown-item" href="#">Dropdown item 4</a></li>
                    </ul>
                </li>
            </ul>
        </div>
        <div class="d-flex align-items-center">
            <p class="text-white mb-0">Secondary navbar</p>
            <button class="navbar-toggler ml-2" type="button" data-toggle="collapse"
                data-target="#navbar-default-primary" aria-controls="navbar-default-primary"
                aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
        </div>
    </div>
</nav>
<nav class="navbar navbar-expand-lg navbar-transparent navbar-light mb-4">
    <div class="container position-relative">
        <a class="navbar-brand mr-lg-3" href="#">
            <img class="navbar-brand-dark" src="../../assets/brand/rocket.svg" alt="menuimage">
            <img class="navbar-brand-light" src="../../assets/brand/rocket-dark.svg" alt="menuimage">
        </a>
        <div class="navbar-collapse collapse" id="navbar-default-primary">
            <div class="navbar-collapse-header">
                <div class="row">
                    <div class="col-6 collapse-brand">
                        <a href="#">
                            <img src="../../assets/img/brand/rocket-dark.svg" alt="menuimage">
                        </a>
                    </div>
                    <div class="col-6 collapse-close">
                        <i class="fas fa-times" data-toggle="collapse" role="button"
                            data-target="#navbar-default-primary" aria-controls="navbar-default-primary"
                            aria-expanded="false" aria-label="Toggle navigation"></i>
                    </div>
                </div>
            </div>
            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                <li class="nav-item">
                    <a href="#" class="nav-link">About</a>
                </li>
                <li class="nav-item dropdown">
                    <a href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="fas fa-angle-down nav-link-arrow"></i>
                        <span class="nav-link-inner-text">Dropdown 2 </span>
                    </a>
                    <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">Dropdown item 1</a></li>
                        <li><a class="dropdown-item" href="#">Dropdown item 2</a></li>
                        <li class="dropdown-submenu">
                            <a href="#" class="dropdown-toggle dropdown-item d-flex justify-content-between align-items-center" aria-haspopup="true" aria-expanded="false">Dropdown item 3 <i class="fas fa-angle-right nav-link-arrow"></i></a>
                            <ul class="dropdown-menu">
                                <li>
                                    <a href="#" class="dropdown-item">Submenu item 1</a>
                                </li>
                                <li>
                                    <a href="#" class="dropdown-item">Submenu item 2</a>
                                </li>
                            </ul>
                        </li>
                        <li><a class="dropdown-item" href="#">Dropdown item 4</a></li>
                    </ul>
                </li>
            </ul>
        </div>
        <div class="d-flex align-items-center">
            <p class="text-dark mb-0">Dark text</p>
            <button class="navbar-toggler ml-2" type="button" data-toggle="collapse"
                data-target="#navbar-default-primary" aria-controls="navbar-default-primary"
                aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
        </div>
    </div>
</nav>
{{< /example >}}

## Headroom

In order to enable headroom for the navbar add the class `.headroom` to the main `.navbar` element.

{{< highlight javascript >}}
if ($('.headroom')[0]) {
    var headroom = new Headroom(document.querySelector("#navbar-main"), {
        offset: 0,
        tolerance: {
            up: 0,
            down: 0
        },
    });
    headroom.init();
}
{{< /highlight >}}
