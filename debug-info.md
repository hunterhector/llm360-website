layout: default # Use the theme's default layout
title: Debug Information
permalink: /debug-info/
---

# Jekyll Debug Information

This page is for debugging purposes. Please copy the values below.

* **Site URL:** `{{ site.url }}`
* **Site Baseurl:** `{{ site.baseurl }}`
* **Page URL:** `{{ page.url }}`
* **Page Path:** `{{ page.path }}`
* **Relative URL for /assets/css/main.css:** `{{ '/assets/css/main.css' | relative_url }}`
* **Absolute URL for /assets/css/main.css:** `{{ '/assets/css/main.css' | absolute_url }}`
* **Canonical URL (from theme's head.liquid):** `{{ page.url | replace:'index.html','' | absolute_url }}`

---
</script>
