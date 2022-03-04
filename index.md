---
title: ESP Breadboard Testkit
description: ESP32 DEVKIT for BREADBOARDS
layout: default
---

## First of all
> This site is under construction. I would therefore like to apologise in advance if something is not presented correctly. But I am very interested in constantly improving my presentation. Therefore, all comments are very welcome.

## Motivation

Protoyping a circuit makes the breadboard an indispensable helper. When building circuits around an ESP32, it is essential to use a DEVKIT. Most DEVKITs have their own USB port and can therefore also provide the power supply (5V and 3V3). 
But there is a problem with that. The designs I know are using 2.54 PINHEAD, but unfortunately they only fit on the standard breadboards in such a way that all the holes are occupied. They are therefore not usable. As a consequence, cable bridges are often used. However, these have the major disadvantage that they make circuits very susceptible to interference. For example, when trying to power an ESP-DEVKIT externally and not via USB, I just observed the crash due to the chip-internal BROWNOUT detection when initialising the WiFi connection.


## Working space
[Link to markdown page](./index_old.html).

[Link to another page](./another-page.html).

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
