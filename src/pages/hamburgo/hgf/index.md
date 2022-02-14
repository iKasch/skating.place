---
setup: |
  import SkateSpotDetails from '../../../components/SkateSpotDetails.astro'
layout: "../../../layouts/SkateSpotLayout.astro"
title: Heiligengeistfeld
shortname: HGF
mapsLink: https://goo.gl/maps/hpAzU9QpGvqL2aev6
description: HGF ist okay, aber die RSB ist auch toll.
image: /assets/images/hgf.jpeg
---

<SkateSpotDetails title={frontmatter.title} shortname={frontmatter.shortname} mapsLink={frontmatter.mapsLink} description={frontmatter.description} image={frontmatter.image} />
