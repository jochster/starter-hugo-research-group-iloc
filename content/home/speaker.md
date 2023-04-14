---
widget: "portfolio"
headless: true

weight: 50
# ... Put Your Section Options Here (title etc.) ...
title: Invited Speakers
subtitle: ''
active: false

content:
  # Choose which content to display in the widget
  filters:
    # Folders to display content from
    folders:
      - speaker
    # Uncomment below to only show content with specific tags:
#    tags:
#      - Machine Learning
    # Uncomment below to exclude content with specific tags:
#    exclude_tags:
#      - preface    
    # Uncomment below to show specific Hugo Page kinds
    kinds:
      - page
#      - section

  # Field to sort by, such as Date or Title
  sort_by: 'Date'
  sort_ascending: false

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `filter_button` below.
  # filter_button:
  #  - name: All
  #    tag: '*'
  #  - name: Deep Learning
  #    tag: Deep Learning
  #  - name: Other
  #    tag: Demo

  # Default filter toolbar button (e.g. 0 corresponds to the first `filter_button` instance above)
  filter_default: 0

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'
  # Choose a listing view
  # view: masonry
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  #   masonry
  view: 5
  # For Showcase view, flip alternate rows?
  flip_alt_rows: true
  # background:
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

---
