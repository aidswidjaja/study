---
title: "YAML Front Matter and Metadata"
layout: default
nav_exclude: true
search_exclude: true
---

# Chapter heading

```
---
title: "Year 9 Maths Chapter 8: Quadratic expressions and algebraic fractions"
layout: default
parent: Maths
nav_order: 8
---
```

**nav_order is relative to the parent**

***

# References to other chapters

```
*You will want to refer to [Year 9 Maths Chapter 8](y9c8.html) for more advanced skills. This section is more basic, and omits FOIL, difference of two squares, perfect squares, and more advanced concepts.*
```

**note that Markdown italics is used for references... `*your content here*` == *your content here*.

***

# nav_exclude and search_exclude == true

```
---
title: 404 Error
layout: default
nav_exclude: true
search_exclude: true
---
```

