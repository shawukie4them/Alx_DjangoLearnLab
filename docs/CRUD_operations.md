# CRUD Operations in Django ORM

This document summarizes how to perform CRUD operations using Django's ORM.

---

## *1. Create a Book*
```python
from bookshelf.models import Book
book1 = Book.objects.create(title="1984", author="George Orwell", publication_year=1949)
print(book1)