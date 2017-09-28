---
title: "Mobiles Test Farm: Create Your Own"
header:
  overlay_image: /assets/images/mobile_devices_test_farm-android.png
  overlay_filter: rgba(0, 100, 255, 0.2)
  caption: "Photo credit: [**Testdroid**](https://bitbar.com)"
  cta_url: "https://bitbar.com"
categories:
  - Layout
  - Uncategorized
tags:
  - edge case
  - image
  - layout
last_modified_at: 2016-11-03T11:45:09-04:00
---

**Why** & **how** to build a low costs distributed grid for the testing of mobiles.

This post demonstrates automating the exution of parallel application tests on real iOS and Android devices.

## Overlay filter

You can use it by specifying the opacity (between 0 and 1) of a black overlay like so:

![transparent black overlay]({{ "/assets/images/mm-header-overlay-black-filter.jpg" | absolute_url }})

```yaml
excerpt: "This post should [...]"
header:
  overlay_image: /assets/images/mobile_devices_test_farm-android.png
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  cta_label: "More Info"
  cta_url: "https://unsplash.com"
```

Or if you want to do more fancy things, go full rgba:

![transparent red overlay]({{ "/assets/images/mm-header-overlay-red-filter.jpg" | absolute_url }})

```yaml
excerpt: "This post should [...]"
header:
  overlay_image: /assets/images/mobile_devices_test_farm-android.png
  overlay_filter: rgba(255, 0, 0, 0.5)
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  cta_label: "More Info"
  cta_url: "https://unsplash.com"
```