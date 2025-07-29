---
title: Process Optimization of PµSL for Assembly-Free Fabrication of Micro Transmission Mechanisms

event: 2024 MRS Fall Meeting
event_url: https://www.mrs.org/meetings-events/annual-meetings/2024-mrs-fall-meeting/

location: Hynes Convention Center, Boston, MA, USA
address:
  # street: 450 Serra Mall
  city: Boston
  region: MA
  # postcode: '94305'
  country: United States

projects:
- R17

summary: Poster presentation in the 2024 MRS Fall Meeting & Exhibit
abstract: 'Micro transmission mechanisms (μTMs) hold significant potential in the automobile, MEMS, and aerospace industries; however, their fabrication and assembly present challenges due to their diminutive size. Projection Micro Stereolithography (PμSL) offers a promising solution, achieving micron-level pixel resolution for efficient μTM fabrication. Nevertheless, the Gaussian distribution of pixel radiance in PμSL poses a limitation by causing unintended bonding of clearance between two workpieces, hindering assembly-free fabrication of μTMs. Increasing the designed clearance is one solution, yet it compromises the transmission efficiency and compactness of μTMs. Aiming to achieve assembly-free fabrication of μTMs with small clearance between workpieces, we propose an optimized additive manufacturing method for PμSL system. Firstly, we developed a model to simulate cured region based on pixel-level Gaussian irradiance distribution. Based on experiments of curing profile characterization in horizontal and depth directions, the model was calibrated per photosensitive resins and PμSL system. Our findings indicate that the unintended bonding of clearance results from the residual irradiance exceeding the critical exposure dose, initiating photopolymerization at gaps. To address this, we introduced a grayscale pixel compensation method to minimize overexposure and underexposure. Additionally, we implemented a novel exposure strategy, which divides the projection pattern into several segments and project them separately. This approach allows the residual irradiance at clearance to dissipate, preventing it from reaching the critical dose and thereby reducing the minimum achievable clearance to 34 µm (equivalent to the size of four pixels in our PμSL system), which is notably small given the Gaussian radius is six pixels in our PμSL system. Our method has proven effective in the assembly-free fabrication of various microstructures, including micro planetary herringbone gears, bar-linkage mechanisms, and microchannels, using a range of materials such as photo-sensitive resin, polymer-derived ceramics, and alumina ceramics. The proposed exposure strategy holds high potential for various applications, such as micro-transmission mechanisms, MEMS, and microfluidics.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-12-05T20:00:00Z'
date_end: '2024-12-05T22:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - Mingpei Cang
  - Huachen Cui

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Banner of MRS24F'
  focal_point: 'Center'

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
# url_code: 'https://github.com'
# url_pdf: ''
# url_slides: 'https://slideshare.net'
# url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---

![Me at the poster session](photo_at_the_event.jpg "Me at the poster session")

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}} -->

<!-- Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->
