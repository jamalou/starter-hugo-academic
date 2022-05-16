---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

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

  # Contact details (edit or remove options as required)
  email: gait3@eurecom.fr
  address:
    street: EURECOM, Campus SophiaTech, 450 Route des Chappes, CS 50193
    city: '06904 Biot Sophia Antipolis cedex, France' 
    country: FRANCE
    country_code: FR
  coordinates:
    latitude: '43.61460349417259'
    longitude: '7.071563820262212'
design:
  columns: '2'
---
