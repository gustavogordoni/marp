---
header: Bubble sort
transition: fade
style: |
  /* Define the style of morphable elements (Requires Chrome 133 and later) */
  [data-morph] {
    view-transition-name: attr(data-morph type(<custom-ident>), none);
  }

  /* Global style */
  section {
    font-size: 60px;
  }
---

<span data-morph="bar7">███████</span> 7
<span data-morph="bar5">█████</span> 5
<span data-morph="bar3">███</span> 3
<span data-morph="bar9">█████████</span> 9

---

<span data-morph="bar5">█████</span> 5
<span data-morph="bar7">███████</span> 7
<span data-morph="bar3">███</span> 3
<span data-morph="bar9">█████████</span> 9

---

<span data-morph="bar5">█████</span> 5
<span data-morph="bar3">███</span> 3
<span data-morph="bar7">███████</span> 7
<span data-morph="bar9">█████████</span> 9

---

<span data-morph="bar3">███</span> 3
<span data-morph="bar5">█████</span> 5
<span data-morph="bar7">███████</span> 7
<span data-morph="bar9">█████████</span> 9