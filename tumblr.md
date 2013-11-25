---
layout: page
title: "Tumblr"
description: "Our Tumblr"
---
{% include JB/setup %}

<script type="text/javascript">
    // The variable "tumblr_api_read" is now set.
    document.write(
        '<a href="' + tumblr_api_read['posts'][0]['url'] + 
        '">My most recent Tumblr post</a>'
    );
</script>

<!-- Strange issue going on with replacement of " with &apos; --> 