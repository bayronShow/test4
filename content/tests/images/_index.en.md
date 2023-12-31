---
description: Some testing for different styles of image links
title: Images
---

Some testing for different styles of image links.

## Markdown

### Resource SVG

![Magic](test.svg?classes=shadow)

### Relative to page

![Magic](magic.gif?classes=shadow)

### Relative to page up level

![Magic](../images/magic.gif?classes=shadow&height=50px)

### Static SVG

![Logo](/images/logo.svg?classes=shadow&height=50px)

### External fully qualified

![Minion](https://octodex.github.com/images/minion.png?classes=shadow&height=50px)

### External without scheme

![Minion](//octodex.github.com/images/minion.png?classes=shadow&height=50px)

### External without scheme and scheme separator

![Minion](octodex.github.com/images/minion.png?classes=shadow&height=50px)

## HTML

### Resource SVG

<p><img src="test.svg?classes=shadow"></p>

### Relative to page

<p><img src="magic.gif?classes=shadow"></p>

### Relative to page up level

<p><img src="../images/magic.gif?classes=shadow&height=50px"></p>

### Static SVG

<p><img src="/images/logo.svg?classes=shadow&height=50px"></p>

### External fully qualified

<p><img src="https://octodex.github.com/images/minion.png?classes=shadow&height=50px"></p>

### External without scheme

<p><img src="//octodex.github.com/images/minion.png?classes=shadow&height=50px"></p>

### External without scheme and scheme separator

<p><img src="octodex.github.com/images/minion.png?classes=shadow&height=50px"></p>
