python manage.py shell
Book.objects.create(title="1984", author="George Orwell", publication_year=1949)
<Book: 1984>
Book.objects.all()  # <QuerySet [<Book: 1984>]>