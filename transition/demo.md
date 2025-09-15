---
marp: true
theme: gaia
class: gaia lead
headingDivider: 1
paginate: true
header: Marp CLI Experimental
footer: Transition showcase
backgroundImage: linear-gradient(-20deg, rgba(0, 0, 0, 0.3), transparent)
_paginate: false
_header: ''
_footer: ''

style: |
  @keyframes marp-outgoing-transition-vertical-scroll {
    from { transform: translateY(0%); }
    to { transform: translateY(-100%); }
  }
  @keyframes marp-incoming-transition-vertical-scroll {
    from { transform: translateY(100%); }
    to { transform: translateY(0%); }
  }

  @keyframes marp-outgoing-transition-vflip {
    0% { animation-timing-function: ease-in; }
    50% {
      transform: perspective(100vw) translateZ(-100vw) rotateX(-90deg);
      opacity: 0.5;
      animation-timing-function: step-end;
    }
    100% { opacity: 0; }
  }
  @keyframes marp-incoming-transition-vflip {
    0% {
      animation-timing-function: step-start;
      opacity: 0;
    }
    50% {
      transform: perspective(100vw) translateZ(-100vw) rotateX(90deg);
      opacity: 0.5;
      animation-timing-function: ease-out;
    }
  }

  header, footer { text-align: center; color: currentcolor; }
  section.small-code pre { font-size: 68%; 
  }
  
---

# Marp CLI experimental

**Transition showcase** 🪄

# clockwise

<!-- _backgroundColor: #774ED8 -->
<!-- _transition: clockwise -->

```markdown
<!-- transition: clockwise -->
```

# counterclockwise

<!-- _backgroundColor: #4996C8 -->
<!-- _transition: counterclockwise -->

```markdown
<!-- transition: counterclockwise -->
```

# cover

<!-- _backgroundColor: #6EB35E -->
<!-- _transition: cover -->

```markdown
<!-- transition: cover -->
```

# coverflow

<!-- _backgroundColor: #ECD03F -->
<!-- _transition: coverflow -->

```markdown
<!-- transition: coverflow -->
```

# cube

<!-- _backgroundColor: #F39C3C -->
<!-- _transition: cube -->

```markdown
<!-- transition: cube -->
```

# cylinder

<!-- _backgroundColor: #EA5555 -->
<!-- _transition: cylinder -->

```markdown
<!-- transition: cylinder -->
```

# diamond

<!-- _backgroundColor: #774ED8 -->
<!-- _transition: diamond -->

```markdown
<!-- transition: diamond -->
```

# drop

<!-- _backgroundColor: #4996C8 -->
<!-- _transition: drop -->

```markdown
<!-- transition: drop -->
```

# explode

<!-- _backgroundColor: #6EB35E -->
<!-- _transition: explode -->

```markdown
<!-- transition: explode -->
```

# fade

<!-- _backgroundColor: #ECD03F -->
<!-- _transition: fade -->

```markdown
<!-- transition: fade -->
```

# fade-out

<!-- _backgroundColor: #F39C3C -->
<!-- _transition: fade-out -->

```markdown
<!-- transition: fade-out -->
```

# fall

<!-- _backgroundColor: #EA5555 -->
<!-- _transition: fall -->

```markdown
<!-- transition: fall -->
```

# flip

<!-- _backgroundColor: #774ED8 -->
<!-- _transition: flip -->

```markdown
<!-- transition: flip -->
```

# glow

<!-- _backgroundColor: #4996C8 -->
<!-- _transition: glow -->

```markdown
<!-- transition: glow -->
```

# implode

<!-- _backgroundColor: #6EB35E -->
<!-- _transition: implode -->

```markdown
<!-- transition: implode -->
```

# in-out

<!-- _backgroundColor: #ECD03F -->
<!-- _transition: in-out -->

```markdown
<!-- transition: in-out -->
```

# iris-in

<!-- _backgroundColor: #F39C3C -->
<!-- _transition: iris-in -->

```markdown
<!-- transition: iris-in -->
```

# iris-out

<!-- _backgroundColor: #EA5555 -->
<!-- _transition: iris-out -->

```markdown
<!-- transition: iris-out -->
```

# melt

<!-- _backgroundColor: #774ED8 -->
<!-- _transition: melt -->

```markdown
<!-- transition: melt -->
```

# overlap

<!-- _backgroundColor: #4996C8 -->
<!-- _transition: overlap -->

```markdown
<!-- transition: overlap -->
```

# pivot

<!-- _backgroundColor: #6EB35E -->
<!-- _transition: pivot -->

```markdown
<!-- transition: pivot -->
```

# pull

<!-- _backgroundColor: #ECD03F -->
<!-- _transition: pull -->

```markdown
<!-- transition: pull -->
```

# push

<!-- _backgroundColor: #F39C3C -->
<!-- _transition: push -->

```markdown
<!-- transition: push -->
```

# reveal

<!-- _backgroundColor: #EA5555 -->
<!-- _transition: reveal -->

```markdown
<!-- transition: reveal -->
```

# rotate

<!-- _backgroundColor: #774ED8 -->
<!-- _transition: rotate -->

```markdown
<!-- transition: rotate -->
```

# slide

<!-- _backgroundColor: #4996C8 -->
<!-- _transition: slide -->

```markdown
<!-- transition: slide -->
```

# star

<!-- _backgroundColor: #6EB35E -->
<!-- _transition: star -->

```markdown
<!-- transition: star -->
```

# swap

<!-- _backgroundColor: #ECD03F -->
<!-- _transition: swap -->

```markdown
<!-- transition: swap -->
```

# swipe

<!-- _backgroundColor: #F39C3C -->
<!-- _transition: swipe -->

```markdown
<!-- transition: swipe -->
```

# swoosh

<!-- _backgroundColor: #EA5555 -->
<!-- _transition: swoosh -->

```markdown
<!-- transition: swoosh -->
```

# wipe

<!-- _backgroundColor: #774ED8 -->
<!-- _transition: wipe -->

```markdown
<!-- transition: wipe -->
```

# wiper

<!-- _backgroundColor: #4996C8 -->
<!-- _transition: wiper -->

```markdown
<!-- transition: wiper -->
```

# zoom

<!-- _backgroundColor: #6EB35E -->
<!-- _transition: zoom -->

```markdown
<!-- transition: zoom -->
```

# And more, make your own!

<!-- _class: lead invert -->
<!-- _transition: vertical-scroll -->
<!-- _footer: '**Example**: vertical-scroll' -->

<!-- prettier-ignore-start -->

```css
@keyframes marp-outgoing-transition-vertical-scroll {
  from { transform: translateY(0%); }
  to { transform: translateY(-100%); }
}

@keyframes marp-incoming-transition-vertical-scroll {
  from { transform: translateY(100%); }
  to { transform: translateY(0%); }
}
```

<!-- prettier-ignore-end -->

# Try making more creative transitions!

<!-- _class: lead invert small-code -->
<!-- _backgroundColor: #0bf -->
<!-- _transition: vflip 1s -->
<!-- _footer: '**Example**: vflip' -->

<!-- prettier-ignore-start -->

```css
@keyframes marp-outgoing-transition-vflip {
  0% { animation-timing-function: ease-in; }
  50% {
    transform: perspective(100vw) translateZ(-100vw) rotateX(-90deg);
    opacity: 0.5;
    animation-timing-function: step-end;
  }
  100% { opacity: 0; }
}
@keyframes marp-incoming-transition-vflip {
  0% {
    animation-timing-function: step-start;
    opacity: 0;
  }
  50% {
    transform: perspective(100vw) translateZ(-100vw) rotateX(90deg);
    opacity: 0.5;
    animation-timing-function: ease-out;
  }
}
```

<!-- prettier-ignore-end -->

# Marp CLI experimental

**Transition showcase** 🪄

https://github.com/marp-team/marp-cli/issues/447

<!-- header: "" -->
<!-- footer: "" -->
<!-- paginate: false -->
<!-- _transition: fade -->

---

<!-- _class: invert lead -->

Marp CLI's preview mode `--preview` can try transitions easily!

```bash
marp --template bespoke --bespoke.transition --preview ./transition.md
```

Experimental transition is depending on [Shared Element Transitions proposal](https://github.com/WICG/shared-element-transitions), and available in Marp CLI v2.0.0 and later + Chrome/Chromium 101 and later w/ "documentTransition API" experiment.
