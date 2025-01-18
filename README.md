# My Ublock Filters for YouTube

Ublock > Config Button > My Filters tab > Paste this filter

```
! Title: ShortsRemover
! Updated: 27/12/2024
! Licence: MIT

! https://www.youtube.com
! youtube.com##.ytp-ce-element

! https://www.youtube.com

! Recommendation sections that appear in YouTube search results.
www.youtube.com##ytd-search ytd-shelf-renderer.style-scope

! Carousel sections (like Shorts or similar carousels) that appear in YouTube search results.
www.youtube.com##ytd-reel-shelf-renderer

! Shorts from Youtube homepage.
www.youtube.com##ytd-rich-section-renderer

! Shorts from Youtube search results.
youtube.com##ytd-video-renderer.style-scope.ytd-item-section-renderer div#dismissible:has(a[href*="/shorts/"])

! Removes the "Shorts" entry from the sidebar menu.
youtube.com##ytd-guide-entry-renderer:has-text(Shorts)
```
