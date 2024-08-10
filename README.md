# digital-marketing-tasks
# Task 1: Google Analytics Setup

## Task Description:
I have set up Google Analytics on my website to track visitor data.

### Steps Followed:
1. First, I created a [Google Analytics account](https://analytics.google.com/analytics/web/provision/?authuser=0#/p453724982/reports/intelligenthome).
2. Then, I created a new property and added my website URL.
3. Google Analytics provided me with a tracking code, which I inserted into the head section of my website's HTML.

### Tracking Code Example:
```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-X7LFCCERHV"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-X7LFCCERHV');
</script>
