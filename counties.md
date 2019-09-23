# Counties

Retrieves all counties from the database.

## Request

| Property                 | Value            |
| ------------------------ | ---------------- |
| **URL**                  | `/api/counties`  |
| **Method**               | `GET`            |
| **Auth required**        | NO               |
| **Permissions required** | None             |
| **Data constraints**     | `{}`             |

## Success Responses

### No content
**Code** : `204 No Content`
```json
[]
```

### Success
**Code** : `200 Success`
```json
[
  {
    "id": 1,
    "name": "Rosiori de Vede"
  }
]
```
