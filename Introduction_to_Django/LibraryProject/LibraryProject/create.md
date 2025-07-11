python manage.py shell
new_book = Book(title="1984", author="George Orwell",publication_year=1949)
new_book.save()
Book.objects.all()  # <QuerySet [<Book: 1984>]>