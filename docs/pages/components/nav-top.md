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
<nav class="fd-top-nav">
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
                <a class="fd-top-nav__dropdown fd-top-nav__link fd-popover__control active" aria-controls="jhqDa1"
                aria-expanded="false" aria-haspopup="true" role="tab">More</a>
                <div class="fd-popover__body fd-popover__body--right fd-popover__body--no-arrow"
                aria-hidden="true" id="jhqDa1">
                    <nav class="fd-menu">
                        <ul class="fd-menu__list">
                            <li>
                                <a class="fd-menu__item fd-menu__item--with-arrow" aria-controls="jhqDa3" aria-expanded="false" aria-haspopup="true" role="tab">Option 1</a>
                                <div class="fd-popover__body fd-popover__body--right fd-popover__body--inline fd-popover__body--no-arrow" aria-hidden="true" id="jhqDa3">
                                    <nav class="fd-menu">
                                        <ul class="fd-menu__list">
                                            <li><a href="#" class="fd-menu__item">Option 1</a></li>
                                            <li><a href="#" class="fd-menu__item">Option 2</a></li>
                                            <li><a href="#" class="fd-menu__item">Option 3</a></li>
                                            <li><a href="#" class="fd-menu__item">Option 4</a></li>
                                        </ul>
                                    </nav>
                                </div>
                            </li>
                            <li><a href="#" class="fd-menu__item">Option 2</a></li>
                            <li><a href="#" class="fd-menu__item">Option 3</a></li>
                            <li><a href="#" class="fd-menu__item">Option 4</a></li>
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
