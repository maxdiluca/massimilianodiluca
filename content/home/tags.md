+++
# Tag Cloud widget.
widget = "tag_cloud"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Publications by Topic"
subtitle = "Research keywords"

[content]
  # Choose the taxonomy from `config.toml` to display (e.g. tags, categories)
  taxonomy = "tags"

  # Choose how many tags you would like to display (0 = all tags)
  count = 36

  # Main labels checked against the publication label matrix.
  featured = ["haptics", "multisensory perception", "virtual reality", "temporal perception", "vision", "computational modeling"]

  # Keep the cloud useful for navigation by hiding one-off keywords.
  min_count = 2

[design]
  # Minimum and maximum font sizes (1.0 = 100%).
  font_size_min = 0.4
  font_size_max = 2.0
+++
