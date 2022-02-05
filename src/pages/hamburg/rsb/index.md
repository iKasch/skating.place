---
setup: |
  import SkateSpotDetails from '../../../components/SkateSpotDetails.astro'
  import image from './rsb.jpg'
layout: "../../../layouts/SkateSpotLayout.astro"
title: Rollschuhbahn
shortname: RSB
mapsLink: https://g.page/EisArenaHamburg
description: RSB ist okay, aber HGF ist auch toll.
---

<SkateSpotDetails title={frontmatter.title} shortname={frontmatter.shortname} mapsLink={frontmatter.mapsLink} description={frontmatter.description} image={image} />
