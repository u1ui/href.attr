# [u1-href] - attribute
Every element can be a link

## Description

This attribute allows you to turn any element into a link by simply adding the `u1-href` attribute to it.
`Ctrl + click` will open the link in a new tab.
Interactive elements such as buttons, input fields, etc. inside the pseudo-link element prevent the link from being opened.
XSS attacks are prevented by disallowing the `javascript:` protocol.

## Ussage

```html
<div u1-href="http://schwups.ch" u1-href-target=_blank>
    Pseudo link
</div>
```

## Install

```html
<script src="https://cdn.jsdelivr.net/gh/u1ui/href.attr@x.x.x/href.min.js" type=module>
```

## Demos

[minimal.html](http://gcdn.li/u1ui/href.attr@main/tests/minimal.html)  
[test.html](http://gcdn.li/u1ui/href.attr@main/tests/test.html)  

## Note

Always offer an A-Tag with the same link. Screen readers do not recognize that this is a link!

## About

- MIT License, Copyright (c) 2022 <u1> (like all repositories in this organization) <br>
- Suggestions, ideas, finding bugs and making pull requests make us very happy. ♥
