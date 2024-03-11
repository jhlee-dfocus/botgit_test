---
date: 2024-03-01
title: DfocusGPT로 자동 상담 챗봇 만들기
linkTitle: DfocusGPT 챗봇 출시
description: >
  DfocusGPT로 만든 챗봇은 LLM이 가진 능력을 기업 고유의 일상 업무에 활용하여 생산성을 높이는데 사용됩니다.  
author: Jungho Lee ([@DfocusSns](https://www.facebook.com/DfocusSns))
resources:
  - src: "**.{png,jpg}"
    title: "Image #:counter"
    params:
      byline: "Photo: Riona MacNamara / CC-BY-CA"
---

**This is a typical blog post that includes images.**

The front matter specifies the date of the blog post, its title, a short description that will be displayed on the blog landing page, and its author.

## Including images

Here's an image (`featured-sunset-get.png`) that includes a byline and a caption.

{{< imgproc sunset Fill "600x300" >}}
Fetch and scale an image in the upcoming Hugo 0.43.
{{< /imgproc >}}

The front matter of this post specifies properties to be assigned to all image resources:

```
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
  params:
    byline: "Photo: Riona MacNamara / CC-BY-CA"
```

To include the image in a page, specify its details like this:

```
{{< imgproc sunset Fill "600x300" >}}
Fetch and scale an image in the upcoming Hugo 0.43.
{{< /imgproc >}}
```

The image will be rendered at the size and byline specified in the front matter.


