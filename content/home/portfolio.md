+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = false  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 45  # Order that this section will appear.

title = "Open Research Resources, Software, and Translational Outputs"
subtitle = "Platforms, datasets, software, demonstrators, and infrastructure produced by the research programme."

[content]
  # Page type to display. E.g. project.
  page_type = "portfolio"

  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.

  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0

  [[content.filter_button]]
    name = "Flagship"
    tag = "Flagship"

  [[content.filter_button]]
    name = "Software"
    tag = "Software"

  [[content.filter_button]]
    name = "Demos"
    tag = "Demos"

  [[content.filter_button]]
    name = "Infrastructure"
    tag = "Infrastructure"

  [[content.filter_button]]
    name = "Archive"
    tag = "Archive"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = modified by max
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = true

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"

  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"

  # Background image.
  # image = "background.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true

[advanced]
 # Custom CSS.
 css_style = ""

 # CSS class.
 css_class = ""
+++

### Flagship open resources

These resources are intended for use beyond the lab: they support comparison, reuse, teaching, replication, and new research.

- **XR Text Trove**: an open catalogue and analysis of XR text entry techniques, connected to the CHI 2025 TEXT paper and Google-supported work.
- **Locomotion Vault**: a public resource for analysing and comparing VR locomotion techniques.
- **ARME / JAMS resources**: research platforms for augmented and virtual music ensemble rehearsal, connected to MyJAMS and spin-out activity.
- **Virtuoso Strings dataset**: open string ensemble recordings and onset annotations for timing analysis and music information retrieval, published through GitHub and listed on the University of Birmingham research portal.

### Software and reproducible methods

These tools support reproducible measurement and analysis in perception science, haptics, and XR.

### Demonstrators and public engagement

These demonstrations translate perceptual science into interactive systems for public engagement, teaching, industry discussion, and technology evaluation.

### Research infrastructure and lab resources

These platforms support collaboration, shared facilities, research training, and translational pathways across the University and external partners.
