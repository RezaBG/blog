Title: FastAPI CRUD
Date: 2024-09-15 10:40
Category: Programming

# FastAPI doesn't require you to use a SQL (relational) database.

FastAPI supports any relational database you want to use. Here's an example using SQLAlchemy, which can be adapted to other databases supported by SQLAlchemy, such as:

- PostgreSQL
- MySQL
- SQLite
- Oracle
- Microsoft SQL Server, etc.

## Query Parameters, Path Parameters, and Body Fields

### Query Parameters
FastAPI makes it easy to add query parameters to your endpoints. They are optional by default and are passed in the URL. Here's an example:

```python
@app.get("/items/")
async def read_items(q: Optional[str] = None):
    return {"q": q}
```
