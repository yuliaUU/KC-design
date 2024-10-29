---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Портфолио
subtitle: 'Человек приходит в сад не только ради собственного наслаждения, но и для того, чтобы испытать неудобства общения с природой. Сад не должен ставить в приоритет ни человека, ни природное окружение– сад должен сталкивать их, заставляя сосуществовать и вступать в живое взаимодействие в те моменты, когда каждая из сред вторгается в область другой.'

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  
  filter_button:
  #- name: All
  #  tag: '*'
  - name: Проекты
    tag: 'projects' 
  - name: Планировки
    tag: 'plans' 
  - name: Реализация
    tag: real
  - name: Визуализация
    tag: visual
  - name: Документация
    tag: docs
  - name: Конкурсы
    tag: comp
  - name: Фотосъемка
    tag: photo
  - name: 3D-прогулка
    tag: 3d

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false


---
