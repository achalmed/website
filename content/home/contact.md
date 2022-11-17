---
# CONTACT
# Una instancia del widget de contacto (Editar HTML en /theme/v5/partials/blocks/contact.html)
widget: contact

# This file represents a page section.
headless: true

# Activate this widget? true/false
active: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

# CUADRO DE NAME, EMAIL Y MESSAGE
content:
  # ¿Vincular automáticamente el correo electrónico y el teléfono o mostrarlo como texto?
  autolink: true

  # Proveedor de formulario de correo electrónico
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # ¿Habilitar el desafío CAPTCHA para reducir el spam?
      captcha: false


  # Detalles de contacto (edite o elimine opciones según sea necesario)

  # EMAIL
  # email: elmer.achalma.09@unsch.edu.pe
  
  # TELÈFONO
  # phone: +51 934 179 301

  # UBICACIÒN
  address:
    street: 450 Serra Mall
    city: Ayacucho
    region: CA
    postcode: '94305'
    country: United States
    country_code: US

  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  
  # DIRECCIÒN
  # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2

  # HORARIO
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com'

  # CONTACTO
  #contact_links:

  # TWITTER
    #- icon: twitter
    #  icon_pack: fab
    #  name: achalmaedison
    #  link: 'https://twitter.com/achalmaedison'
  
  # ZOOM
    #- icon: video
    #  icon_pack: fas
    #  name: Zoom Me
    #  link: 'https://zoom.com'

design:
  columns: '2'
---
