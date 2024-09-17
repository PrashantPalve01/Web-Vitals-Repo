# Web-Vitals-Repo

Explanation:
The <source> elements use the media attribute to specify screen width conditions (e.g., (min-width: 800px) serves the larger image).
The srcset attribute provides the file for that condition.
The browser will select the first source it can display based on the screen size or supported file format.

## How the <picture> Element Affects Web Vitals

1. Largest Contentful Paint (LCP):
Improves loading time by serving smaller, optimized images for mobile devices.
Uses modern image formats (like WebP) to load faster.

2. Cumulative Layout Shift (CLS):
Prevents layout shifts by using fixed width and height for images.

3. First Input Delay (FID):
Reduces browser load by loading optimized images, which helps the page become interactive faster.