---
setup: |
  import SkateSpotDetails from '../../../components/SkateSpotDetails.astro'
layout: "../../../layouts/SkateSpotLayout.astro"
title: Rollschuhbahn
shortname: RSB
mapsLink: https://g.page/EisArenaHamburg
description: RSB ist okay, aber HGF ist auch toll.
image: /assets/images/rsb.jpg
---

<SkateSpotDetails title={frontmatter.title} shortname={frontmatter.shortname} mapsLink={frontmatter.mapsLink} description={frontmatter.description} image={frontmatter.image} />
