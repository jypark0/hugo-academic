---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Automatically link email and phone?
autolink = false

# Email form provider
#   0: Disable email form
#   1: Netlify (requires that the site is hosted by Netlify)`
#   2: formspree.io
email_form = 0

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]
+++

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false
  
design:
  columns: '2'
---
