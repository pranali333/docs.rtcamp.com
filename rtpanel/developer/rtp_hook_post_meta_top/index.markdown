---
title: rtp_hook_post_meta_top
---

### Description


Adds content after .post-title. This is mainly used for the post meta.


### Example



    
    function custom_hook_post_meta_top() { ?>
    <p>This is post meta top</p><?php
    }
    add_action( 'rtp_hook_post_meta_top', 'custom_hook_post_meta_top' );
