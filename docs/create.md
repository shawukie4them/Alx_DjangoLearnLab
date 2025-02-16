# Create a Book

## Command:
```python
from bookshelf.models import Book

# Creating a book entry
book1 = Book.objects.create(title="1984", author="George Orwell", publication_year=1949)

# Verifying the creation
print(book1)