# Update a Book

## Command:
```python
from bookshelf.models import Book

# Fetch the book
book = Book.objects.get(title="1984")

# Updating the title
book.title = "Nineteen Eighty-Four"
book.save()

# Display updated book title
print(book.title)