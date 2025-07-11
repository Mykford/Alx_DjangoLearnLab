python manage.py shell

Book.objects.get(title = "1984")
<Book: hhj>
Book.objects.values()
<QuerySet [{'id': 4, 'title': '1984', 'author': 'George Orwell', 'publication_year': 1949}]>
