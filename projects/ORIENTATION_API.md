# Bangazon Orientation API

## Requirements

1. Using Django and the REST framework application, you will be building the initial, open API for Bangazon.
1. Expose the following resources in your API.
    1. Customer
    1. Order
    1. Product
    1. Department
    1. Computer
    1. Training Program
    1. Product Type
    1. Payment Type
    1. Employee

The initial version is for internal consumption only, so do not require permissions to access, or manipulate, any resources.


> **Pro tip:** Want to put all of your models into individual files inside a `models` sub-directory of a Django application? You can. Let's say you want the `Customer` class to be defined in a `your_app/models/customer.py` module. That's perfectly fine, as long as you make sure that you create `your_app/models/__init__.py` to make that directory a package. Then you can import the class into the `__init__.py` module.
>
>    `from .customer import Customer`
>
> That will ensure that the class is detected when you run `python manage.py makemigrations your_app`

## Resources

As you progress through the project, your manager will discuss some of these topics with you.

* Seeding your database with [fixtures](https://docs.djangoproject.com/en/1.11/howto/initial-data/)
* Custom [management commands](https://docs.djangoproject.com/en/1.10/howto/custom-management-commands/), including [seeding your database](https://docs.djangoproject.com/en/1.11/ref/django-admin/).
* Custom, [empty migrations](https://docs.djangoproject.com/en/1.11/topics/migrations/#data-migrations) to [execute fixtures](http://stackoverflow.com/questions/25960850/loading-initial-data-with-django-1-7-and-data-migrations#25981899).