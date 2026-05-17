+++
# Tag Cloud widget.
widget = "tag_cloud"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Research"
subtitle = ""

[content]
  # Choose the taxonomy from `config.toml` to display (e.g. tags, categories)
  taxonomy = "tags"

  # Choose how many tags you would like to display (0 = all tags)
  count = 36

  # Main labels checked against the publication label matrix.
  featured = ["haptics", "multisensory perception", "extended reality / virtual reality", "temporal perception", "psychophysics", "computational modelling"]

  [[content.featured_topics]]
    label = "haptics"
    display = "Haptics"
    page = "/research-topic/haptics/"
    description = "Touch and force feedback as perceptual signals: tactile sensitivity, softness, skin stretch, vibrotactile guidance, wearable devices, and haptic rendering for interaction."

  [[content.featured_topics]]
    label = "multisensory perception"
    display = "Multisensory Perception"
    page = "/research-topic/multisensory-perception/"
    description = "How the brain combines uncertain signals from vision, touch, audition, and proprioception, and how integration changes with context, action, timing, and prior experience."

  [[content.featured_topics]]
    label = "extended reality / virtual reality"
    display = "Extended Reality"
    page = "/research-topic/extended-reality-virtual-reality/"
    description = "Perceptually grounded XR systems, from virtual hand ownership and hand tracking to locomotion, collision awareness, haptic augmentation, and public research datasets."

  [[content.featured_topics]]
    label = "temporal perception"
    display = "Temporal Perception"
    page = "/research-topic/temporal-perception/"
    description = "The perception and measurement of time: synchrony, temporal order, duration, recalibration, reaction time, stimulus timing, and delays in interactive systems."

  [[content.featured_topics]]
    label = "psychophysics"
    display = "Psychophysics"
    page = "/research-topic/psychophysics/"
    description = "Behavioural methods for measuring perception and action, including thresholds, discrimination, psychometric functions, user evaluation, and response-time analysis."

  [[content.featured_topics]]
    label = "computational modelling"
    display = "Computational Modelling"
    page = "/research-topic/computational-modelling/"
    description = "Models that explain perceptual decisions and guide technology design, including Bayesian cue integration, Kalman filtering, signal processing, simulation, and machine learning."

  # Avoid repeating a narrower version of a principal topic in the keyword cloud.
  exclude = ["virtual reality"]

  # Keep the cloud useful for navigation by hiding one-off keywords.
  min_count = 2

[design]
  # Minimum and maximum font sizes (1.0 = 100%).
  font_size_min = 0.4
  font_size_max = 2.0
+++

Di Luca's research asks how people perceive, predict, and act in dynamic environments, and how that knowledge can be used to design immersive systems that feel responsive, intelligible, and perceptually grounded.
