---
widget: portfolio
headless: true

# ... Put Your Section Options Here (title etc.) ...
title: Presentations
subtitle: Talks & Posters
weight: 25  # section position on page
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '2'

content:
  # Choose which content to display in the widget
  filters:
    # Folders to display content from
    folders:
      - presentations
    # Uncomment below to only show content with specific tags:
#    tags:

  # Field to sort by, such as Date or Title
  sort_by: 'Date'
  sort_ascending: false

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `filter_button` below.
  filter_button:
    - name: All
      tag: '*'
    - name: Posters 
      tag: Posters
    - name: Talks
      tag: Talks

  # Default filter toolbar button (e.g. 0 corresponds to the first `filter_button` instance above)
  filter_default: 0

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'
  # Choose a listing view
  view: showcase
  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
