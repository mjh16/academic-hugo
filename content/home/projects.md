+++
# Projects widget.
# Note: this widget will only display if `content/project/` contains projects.

date = "2016-04-20T00:00:00"
active = true

title = "Projects"
subtitle = ""
widget = "projects"

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "project"

# Order that this section will appear in.
weight = 50

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.
# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
[[filter]]
  name = "All"
  tag = "*"

#[[filter]]
#  name = "College Composition Committee"
#  tag = ".college-comp"

[[filter]]
  name = "ePortflios"
  tag = ".ePortfolio"

[[filter]]
  name = "WPA Summer DIS"
  tag = ".WPA-DIS"

+++
