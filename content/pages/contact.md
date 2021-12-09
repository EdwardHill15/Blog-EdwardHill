---
form_action: /success
form_fields:
- default_value: Your name
  input_type: text
  is_required: true
  label: Name
  name: name
- default_value: Your email address
  input_type: email
  is_required: true
  label: Email
  name: email
- default_value: Please select
  input_type: select
  label: Subject
  name: subject
  options:
  - Error on the site
  - Sponsorship
  - Other
- default_value: Your message
  input_type: textarea
  label: Message
  name: message
- input_type: checkbox
  label: I understand that this form is storing my submitted information so I can
    be contacted.
  name: consent
form_id: contactForm
img_path: images/contact.jpg
layout: contact
seo:
  description: This is the contact page
  extra:
  - keyName: property
    name: og:type
    value: website
  - keyName: property
    name: og:title
    value: Get in Touch
  - keyName: property
    name: og:description
    value: This is the contact page
  - keyName: property
    name: og:image
    relativeUrl: true
    value: images/contact.jpg
  - name: twitter:card
    value: summary_large_image
  - name: twitter:title
    value: Get in Touch
  - name: twitter:description
    value: This is the contact page
  - name: twitter:image
    relativeUrl: true
    value: images/contact.jpg
  title: Get in Touch
submit_label: Send Message
title: Get in Touch
---

To get in touch fill the form below.
