+++
author = "Hugo Authors"
title = "Guide to Thumbnails in Hugo"
date = "2019-03-04"
description = "Guide to Thumbnails in Hugo"
#tags = [
#    "thumbnail",
#]
#thumbnail= "KMDevineBW.jpg.jpg"
images = ["SiDriveMeet.jpg"]
+++
Thumbnails can be enabled easily by setting the `thumbnail` parameter in the frontmatter to an image such as `"KMDevineBW.jpg"`.

Make sure to copy the image the `static/images/` directory.

![Optional Text](images)

If put together, it will look like this (that's in fact this post's frontmatter):

```md
+++
author = "Hugo Authors"
title = "Guide to Thumbnails in Hugo"
date = "2019-03-04"
description = "Guide to Thumbnails in Hugo"
tags = [
    "thumbnail",
]
thumbnail= "images/landscape.jpg"
+++
```
