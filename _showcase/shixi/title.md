---
show: true
width: 3
date: 2021-09-12 00:01:00 +0800
group: Cats
height: 295px
images:
- src: /assets/images/photos/1.png
  desc: Customized Animal Generation
  link: https://picsum.photos/
- src: /assets/images/photos/2.png
  desc: Customized Animal Generation
- src: /assets/images/photos/3.png
  desc: Customized Animal Generation
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}