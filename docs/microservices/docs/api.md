---
title: "API"
linkTitle: "API Documentation"
date: "11-22-2019"
weight: "1"
description: "API Documentation Description"
---

# API documentation

API changes
Changes ...
## Create Item

```
POST /api/items
{
    "title": "item 1 title",
    "body": "item 1 description very long"
}
```

Response 

```
{
    "success": "true",
    "message": "item created successfully"
}
```

## Retrieve Item

```
GET /api/items/1
```

Response

```json
{
    "id": "123",
    "title": "item 123 title",
    "body": "item 123"
}
```