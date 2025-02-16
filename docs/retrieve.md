# Retrieve a Book

## Command:
```python
from bookshelf.models import Book

# Retrieving the book by title
book = Book.objects.get(title="1984")

# Display book details
print(book.title, book.author, book.publication_year)