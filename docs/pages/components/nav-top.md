---
title: Top Navigation
id: navigation
keywords: navigation
sidebar: left-navigation-sidebar
toc: false
permalink: components/nav-top.html
folder: components
summary:
---

The left navigation can always display or expand/collapse using the menu icon within the global navigation.
{: .docs-intro}

> {{ site.data.strings.headerDisclaimer }}

## Top Navigation for bigger devices
{% capture default %}
<nav class="fd-top-nav" id="top-nav">
    <ul class="fd-top-nav__list">
        <li class="fd-top-nav__item">
            <a class="fd-top-nav__link active" href="#">
                Link Item
            </a>
        </li>
        <li class="fd-top-nav__item">
            <a class="fd-top-nav__link is-selected" aira-selected="true" href="#">
                Link Item
            </a>
        </li>
        <li class="fd-top-nav__item">
            <a class="fd-top-nav__link" href="#">
                Link Item
            </a>
        </li>
        <li class="fd-top-nav__item">
            <a class="fd-top-nav__link" href="#">
                Link Item
            </a>
        </li>
        <li class="fd-top-nav__item">
            <a class="fd-top-nav__link" href="#">
                Link Item
            </a>
        </li>
        <li class="fd-top-nav__item">
             <div class="fd-popover fd-popover--right">
                <a href="#" class="fd-top-nav__dropdown fd-top-nav__link fd-popover__control active" aria-controls="jhqDa1"
                aria-expanded="false" aria-haspopup="true" role="tab">More</a>
                <div class="fd-top-nav__popover"
                aria-hidden="true" id="jhqDa1">
                    <nav class="fd-top-nav__menu">
                        <ul class="fd-top-nav__sub-list">
                            <li class="fd-top-nav__sub-item">
                                <a href="#" class="fd-top-nav__sub-link fd-top-nav__sub-link--with-arrow" aria-controls="jhqDa3" aria-expanded="false" aria-haspopup="true" role="tab">Option 1</a>
                                <div class="fd-top-nav__popover fd-top-nav__popover--inline" aria-hidden="true" id="jhqDa3">
                                    <nav class="fd-top-nav__menu">
                                        <ul class="fd-top-nav__sub-list">
                                            <li class="fd-top-nav__sub-item"><a href="#" class="fd-top-nav__sub-link fd-top-nav__sub-link--deep active">Option 1</a></li>
                                            <li class="fd-top-nav__sub-item"><a href="#" class="fd-top-nav__sub-link fd-top-nav__sub-link--deep">Option 2</a></li>
                                            <li class="fd-top-nav__sub-item"><a href="#" class="fd-top-nav__sub-link fd-top-nav__sub-link--deep">Option 3</a></li>
                                            <li class="fd-top-nav__sub-item"><a href="#" class="fd-top-nav__sub-link fd-top-nav__sub-link--deep">Option 4</a></li>
                                        </ul>
                                    </nav>
                                </div>
                            </li>
                            <li class="fd-top-nav__sub-item"><a href="#" class="fd-top-nav__sub-link">Option 2</a></li>
                            <li class="fd-top-nav__sub-item"><a href="#" class="fd-top-nav__sub-link">Option 3</a></li>
                            <li class="fd-top-nav__sub-item"><a href="#" class="fd-top-nav__sub-link">Option 4</a></li>
                        </ul>
                    </nav>
                </div>
            </div>
        </li>
    </ul>
</nav>
{% endcapture %}
{% include display-component.html component=default %}

<br>
