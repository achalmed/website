---
# Una instancia del widget de páginas.
# Documentación: https://wowchemy.com/docs/page-builder/
# se puede cambiar con collection o pages 
widget: collection

# This file represents a page section.
headless: true

# Activate this widget? true/false
active: true

# Order that this section appears on the page.
weight: 60

title: Posts
subtitle:

content:
  # Filtrar por criterios
  filters:
    folders:
      - post
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Elija cuántas páginas le gustaría mostrar (0 = todas las páginas)
  count: 5
  # Elija cuántas páginas le gustaría compensar por
  offset: 0
  ## Orden de páginas: fecha descendente (desc) o ascendente (asc).
  order: desc

design:
  # Elija una vista para los listados:
  view: compact
  columns: '2'
---
