# Django 4.2 MVC Project

This is a web application built using the Django 4.2, a Python-based free open-source web framework. It follows the Model-View-Controller (MVC) architectural pattern.

## Tools Used

This project utilizes several cutting-edge technologies listed below:

1. **Django 4.2**: A high-level Python web framework that encourages rapid development and clean, pragmatic design.
2. **PostgreSQL**: An open-source object-relational database system with robust features.
3. **Supabase**: An open-source firebase alternative to help in scaling your Django 4.2 projects.
4. **OpenAI**: Provides artificial intelligence functionalities to our application.
5. **Celery**: It is used for asynchronous task queuing that allows tasks to run on multiple worker servers.
6. **Tailwind**: A utility-first CSS framework for rapidly building custom user interfaces.
7. **Docker**: An open platform for developing, shipping, and running applications to enable developers to separate applications from their infrastructure.
8. **LangChain**: Open-source natural language processing technology to assist with language-related operations.
9. **qDrant**: A vector similarity search engine with extended filtering capabilities.

## How to Run

To run this project, run this commands.
```bash
pip install -r requirements.txt
python manage.py runserver
```

To run this project locally using docker, follow below steps:

1. Make sure you have docker and docker-compose installed on your machine.
2. Clone the repository to your machine.
3. Navigate to the directory containing `docker-compose.yml` file.
4. Run `docker-compose up`.

(You may need to run the command as a superuser)

This will spin up multiple Docker containers for the Django webapp, PostgreSQL, Supabase, OpenAI, Celery, etc.

## Contributing

Contributions are welcome! Please fork this repository and open a Pull Request to add enhancements, bug fixes, or propose changes.