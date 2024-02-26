---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: hero
    content:
      title: Welcome
      image:
        # Reference an image in your `assets/media/` folder
        filename: logohome.png
      # Add your Call-To-Action (CTA) button and optional icon
       # Add your Hero text here
      text: |-
       Thank you for visiting! Check out our products below. If you have any questions, feel free to reach out. Visit us at 🎬 [Tiktok](tiktok.com) and 📸[IG](instagram.com).  

     
    design:
      # Choose an optional background color, gradient, image, or video
      background:
        gradient_end: '#DEE4EA'
        gradient_start: '#F9FCFF'
        #text_color_light: true









  - block: people
    content:
      title: Products
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Fertilizer
        - Supplies
        - Tools
      sort_by: Params.last_name
      sort_ascending: true
    design:
      # Show user's social networking links? (true/false)
      show_social: false
      # Show user's interests? (true/false)
      show_interests: true
      # Show user's role?
      show_role: true
      # Show user's organizations/affiliations?
      show_organizations: true

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact
      columns: '2'
      background:
        image: 
         filename: background.jpg

--- 