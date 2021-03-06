---
title: Home
hide_title: true
sections:
  - type: section_hero
    template: section_hero
    title: 'Hi, I''m Stackbit Exto Portfolio Theme.'
    section_id: hero
    content: >-
      This section can contain a subtitle or tagline. The recommended length is
      one to three sentences, but can be changed as you prefer.
    actions:
      - type: action
        template: action
        label: Let's talk
        url: /contact
        style: button
  - type: section_portfolio
    template: section_portfolio
    title: Recent Work
    section_id: latest-projects
    subtitle: An optional subtitle of the section
    layout_style: mosaic
    projects_number: 6
    view_all_label: View All
    view_all_url: portfolio
  - type: section_grid
    template: section_grid
    title: What We Do
    section_id: services
    subtitle: An optional subtitle of the section
    col_number: two
    is_numbered: true
    grid_items:
      - type: grid_item
        template: grid_item
        title: Service Title
        content: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
          ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
          fringilla, fringilla.
      - type: grid_item
        template: grid_item
        title: Service Title
        content: >-
          Donec lobortis velit sed suscipit lobortis. Ut non quam metus. Nullam
          a maximus mi. Quisque justo nunc, sollicitudin euismod euismod at,
          tincidunt ut tellus.
      - type: grid_item
        template: grid_item
        title: Service Title
        content: >-
          Sed laoreet magna commodo libero euismod sodales. Nunc ac libero
          convallis, interdum ligula vel, pretium diam. Integer commodo sem at
          dui sollicitudin.
      - type: grid_item
        template: grid_item
        title: Service title
        content: >-
          Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis
          nunc non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
  - type: section_testimonials
    template: section_testimonials
    title: Testimonials
    section_id: testimonials
    subtitle: An optional subtitle of the section
    col_number: three
    testimonials:
      - type: testimonial
        template: testimonial
        author: Sean Salazar
        avatar: images/sean_salazar.jpg
        avatar_alt: Sean Salazar's photo
        content: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
          ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
          fringilla.
      - type: testimonial
        template: testimonial
        author: Aubrey Hoover
        avatar: images/aubrey_hoover.jpg
        avatar_alt: Aubrey Hoover's photo
        content: >-
          Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis
          nunc non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
      - type: testimonial
        template: testimonial
        author: Deegan Wallace
        avatar: images/deegan_wallace.jpg
        avatar_alt: Deegan Wallace's photo
        content: >-
          Sed laoreet magna commodo libero euismod sodales. Nunc ac libero
          convallis, interdum ligula vel, pretium diam.
  - type: section_posts
    template: section_posts
    title: Latest from the Blog
    section_id: latest-posts
    subtitle: An optional subtitle of the section
    posts_number: 3
    col_number: three
    actions:
      - type: action
        template: action
        label: View Blog
        url: blog
        style: button
seo:
  type: stackbit_page_meta
  template: stackbit_page_meta
  title: Stackbit Exto Theme
  description: The preview of the Exto theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Exto Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Exto theme
      keyName: property
    - name: 'og:image'
      value: images/exto_preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Exto Theme
    - name: 'twitter:description'
      value: The preview of the Exto theme
    - name: 'twitter:image'
      value: images/exto_preview.png
      relativeUrl: true
template: advanced
---
