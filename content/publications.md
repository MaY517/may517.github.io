---
title: 'Publications'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections

sections:
  - block: collection
    content:
      title: Publications
      filters:
        # Folders to display content from
        folders:
          - publication
        buttons:
          - name: All
            tag: '*'
          - name: AI
            tag: Deep Learning
          - name: Inversion
            tag: Inverse Problem
          - name: Acoustics
            tag: Acoustics
        default_button_index: 0

      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.

    # design:
    #   # See Page Builder docs for all section customization options.
    #   # Choose how many columns the section has. Valid values: '1' or '2'.
    #   columns: '1'
    #   # Choose a listing view
    #   view: showcase
    #   # For Showcase view, flip alternate rows?
    #   flip_alt_rows: false
---
