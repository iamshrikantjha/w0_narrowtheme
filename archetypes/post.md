---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
tags: ['trend']
categories: ['cat1']
cover: 'https://i.ytimg.com/vi/1hJnHoaBLQo/maxresdefault.jpg'
---

{{ replace .Name "-" " " | title }}

******HOW TO WRITE BLOG******

1. Headings
# heading 1
## heading 2
### heading 3
#### heading 4
##### heading 5
###### heading 6

2. Youtube Video
## Youtube Shortcode

{{< youtube CFEkjzf8DAA >}}

3. Images

![Minion](https://octodex.github.com/images/minion.png)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")
![Elon Image](/images/elon_musk/1.jpeg)

