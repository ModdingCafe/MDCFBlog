---
title: "{{ replace .Name "-" " " | title }}"
date: "{{ now.Format "2006-01-02" }}"
draft: false
# Nếu có youtube_id, featured_image sẽ bị ẩn.
featured_image: "poster.jpg"
youtube_id: 0
# Cách viết (NOTE: spaces-tab, not tab-tab)
#tags:
#  - tag1
#  - tag2
#  - tag3
tags:


# Cách ngắt nội dung vào "Continue Reading":
# gõ dòng <!--more--> vào chỗ muốn cắt.
---