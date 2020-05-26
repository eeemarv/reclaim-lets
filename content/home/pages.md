+++
widget = "pages"  # Use the Pages widget
headless = true  # This file represents a page section.
weight = 30
title = "Posts"
# ... Put Your Section Options Here (title etc.) ...

[content]
page_type = "posts"
count = 5
offset = 0
order = "desc"
[content.filters]
tag = ""
category = ""
publication_type = ""
exclude_featured = false
exclude_past = false
exclude_future = false

[design]
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
view = 2
+++