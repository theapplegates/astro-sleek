---
title: Hello World
description: It's a beautiful world out there.
date: 2022-11-05
---

import { Picture } from '@astrojs/image/components';
import { Picture } from "astro-imagetools/components";

It's a beautiful world out there.

<Picture src={import("/jelly-fish.jpg")} widths={[100, 200, 400, 800, 1600]} sizes="(max-width: 1600px) 100vw, 1600px" alt="descriptive text" />

<Picture
	src="../src/images/jelly-fish.jpg"
	alt="A jelly-fish"
/>

![jelly-fish](../src/images/jelly-fish.jpg)

![A local image](../src/images/jelly-fish.jpg)
