---
title: Scroll bar missing in media tab
---

In some of the themes scrollbar is missing in media tab. This issue is encounter with Bootstrap based themes. Add following CSS code in your theme's style.css file to fix this issue.

    
    <code>body.media {
    overflow-y: scroll;
    }</code>
