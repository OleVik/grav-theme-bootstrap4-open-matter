---
title: Home
published: true
visible: false
body_classes: 'header-image fullwidth'
child_type: item
content:
    items: '@self.children'
    limit: 7
    order:
        by: date
        dir: desc
    pagination: '9'
hide_post_summary: true
post_icon: calendar-o
hide_post_date: true
hide_post_taxonomy: true
hide_git_sync_repo_link: false
continue_link_as_button: false
modular_content:
    items: '@self.modular'
    order:
        by: folder
        dir: dsc
feed:
    description: 'Grav CMS Open Matter Course Hub Description'
    limit: 10
protectEdit: true
hide_page_title: true
---
