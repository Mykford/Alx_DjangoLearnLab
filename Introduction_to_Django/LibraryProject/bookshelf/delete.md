python manage.py shell
from bookshelf.models import Book
book.delete
Book.objects.all().delete() #(1, {'bookshelf.Book': 1})