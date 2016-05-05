# marteinn.se

My personal blog built in AtomicPress.


## Requirements

- Python 2.7


## Getting started

1. Install requirements

    `pip install -r src/requirements/local.txt`

1. Create database

    `python mange.py create_db`

1. (Optional) Add sample data

    `python manage.py prefill fill`

1. Start server

    `python manage.py runserver`

1. Done!

## Commands

- Run application

    `python manage.py runserver`

- Run application (with admin and debug enabled)

    `python manage.py runserver -a -d`

- Generate static assets

    `python manage.py exporter export`

- Upload to S3

    `python manage.py s3 sync`


# License

Marteinn.se is released under the MIT License.
