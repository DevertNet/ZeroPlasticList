---
title: Kitchen
slug: kitchen
metadata:
    description: "List of products for the kitchen without plastic. Get inspired to reduce plastic in your household."

template: blog
content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 5
    pagination: true

---