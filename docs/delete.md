# Delete a Book

## Command:
```python
from bookshelf.models import Book

# Fetch the book
book = Book.objects.get(title="Nineteen Eighty-Four")

# Delete the book
book.delete()

# Verify deletion
print(Book.objects.all())  # Should return an empty queryset