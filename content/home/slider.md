+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = ""

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "COVID-19 Updates"
  content = "We are closed for COVID-19 school closures. More information can be found here. :mask:"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#f04f5c"  # An HTML color value.
  overlay_img = "home/covid-slider.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "COVID-19 Information"
  cta_url = "/covid19/"
  cta_icon_pack = "fas"
  #cta_icon = "graduation-cap"

[[item]]
  title = "Parents"
  content = "Online learning resources, special education information, and the school's report card"
  align = "center"

  overlay_color = "#32a852"  # An HTML color value.
  overlay_img = "home/parents-slider.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "Parent Information"
  cta_url = "/parents/"

[[item]]
  title = "Staff"
  content = "Information and links for current and potential staff"
  align = "center"

  overlay_color = "#3486eb"  # An HTML color value.
  overlay_img = "home/staff-slider.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "Staff Information"
  cta_url = "/staff/"

[[item]]
  title = "About Us"
  content = "Learn about our school, district, and staff"
  align = "center"

  overlay_color = "#c70039"  # An HTML color value.
  overlay_img = "home/about-slider.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "About Us"
  cta_url = "/about/"


+++
