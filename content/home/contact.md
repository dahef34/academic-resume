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
  email: jhefley@sudomail.com
  phone: 619 483 0453
  address:
    street: 100 Brewster Blvd
    city: Camp Lejeune
    region: NC
    postcode: '28547'
    country: United States
    country_code: US
  coordinates:
    latitude: '34.6251'
    longitude: '-77.4013'
  directions: Second floor office w258
  office_hours:
    - 'Friday 10:00 to 13:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/HefleyJustin'


design:
  columns: '2'
---
