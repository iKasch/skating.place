---
setup: |
  import SkateSpotDetails from '../../../components/SkateSpotDetails.astro'
layout: "../../../layouts/SkateSpotLayout.astro"
title: Tempelhofer Feld
shortname: Feld
mapsLink: https://goo.gl/maps/iLfb5ANJyaWR7gbx7
description: Feld Vibes sind best Vibes!
image: /assets/images/tempelhoferfeld.jpg
---

<SkateSpotDetails title={frontmatter.title} shortname={frontmatter.shortname} mapsLink={frontmatter.mapsLink} description={frontmatter.description} image={frontmatter.image} />
