# Class 27 Reading Notes

## Django Models

Models are usually defined in an application's models.py file. They are implemented as subclasses of django.db.models.Model.

```Python
from django.db import models
from django.urls import reverse

class MyModelName(models.Model):
    """A typical class defining a model, derived from the Model class."""

    # Fields
    my_field_name = models.CharField(max_length=20, help_text='Enter field documentation')
    # …

    # Metadata
    class Meta:
        ordering = ['-my_field_name']

    # Methods
    def get_absolute_url(self):
        """Returns the URL to access a particular instance of MyModelName."""
        return reverse('model-detail-view', args=[str(self.id)])

    def __str__(self):
        """String for representing the MyModelName object (in Admin site etc.)."""
        return self.my_field_name
```

### Fields

A model can have an arbitrary number of fields, of any type — each one represents a column of data that we want to store in one of our database tables.

### Define Local Library

in models.py

```Python
from django.db import models

class Genre(models.Model):
    """Model representing a book genre."""
    name = models.CharField(max_length=200, help_text='Enter a book genre (e.g. Science Fiction)')

    def __str__(self):
        """String for representing the Model object."""
        return self.name

```

## Django Admin

The Django admin application can use your models to automatically build a site area that you can use to create, view, update, and delete records.
First, open admin.py.

```Python
from django.contrib import admin
from .models import Author, Genre, Book, BookInstance

admin.site.register(Book)
admin.site.register(Author)
admin.site.register(Genre)
admin.site.register(BookInstance)

```

create a "superuser" account that has full access to the site and all needed permissions using manage.py.

```Python
python3 manage.py createsuperuser
python3 manage.py runserver
```

### Loggin in and Using the Site

To login to the site, open the /admin URL (e.g. http://127.0.0.1:8000/admin) and enter your new superuser userid and password credentials
click the Add link next to each model to start creating a record of that type
When you're done you can press SAVE, Save and add another, or Save and continue editing to save the record.

### Resources

[Django Models](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models#summary)

[Django Admin](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site)

---

[Back to Home](../README.md)
