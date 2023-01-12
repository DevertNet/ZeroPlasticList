---
title: Küche
slug: kueche
metadata:
    description: "Liste von Produkten für die Küche ohne Plastik. Lass dich inspirieren um Plastik in deinem Haushalt zu reduzieren."

template: blog
content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 5
    pagination: true

---