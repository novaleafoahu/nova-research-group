---
# Leave the homepage title empty to use the site title
#title:
date: 2022-10-24
type: landing

sections:


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


---