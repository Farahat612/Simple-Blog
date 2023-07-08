# Django Blog

A simple blog web application developed using Python and Django.

## Project Overview

This project serves as a practice during a learning journey to develop a basic blog web application. It allows users to view blog posts and read their contents.

## Project Structure

The project consists of the following directories and files:

1. **blog** - The main project directory.
   - `asgi.py` - ASGI configuration for the project.
   - `settings.py` - Django settings and configurations for the project.
   - `urls.py` - URL configuration for the project.
   - `wsgi.py` - WSGI configuration for the project.

2. **posts** - The app directory for managing blog posts.
   - `admin.py` - Configuration for Django admin panel.
   - `apps.py` - Configuration for the app.
   - `models.py` - Definition of the `Post` model.
   - `tests.py` - Unit tests for the app.
   - `urls.py` - URL configuration for the app.
   - `views.py` - Views and logic for rendering the blog posts.

3. **templates** - Directory containing HTML templates for rendering the views.
   - `index.html` - Template for rendering the list of blog posts.
   - `post.html` - Template for rendering a single blog post.

4. `manage.py` - Django's command-line utility for managing the project.

## Usage

To run the Django Blog project locally, follow these steps:

1. Install the required dependencies mentioned in the `requirements.txt` file.

2. Set up the project environment and database settings in `settings.py`.

3. Apply database migrations using the command: `python manage.py runserver`

4. Run the development server using the command: `python manage.py runserver`

5. Access the blog application in your web browser at `http://localhost:8000`.

## Features

1. **Viewing Blog Posts**: Users can view a list of blog posts on the home page (`/`) in reverse chronological order. Each post displays the title, creation date, and a truncated preview of the post's content.

2. **Viewing Individual Posts**: Clicking on a post's title takes the user to the individual post view (`/post/<post_id>`), where the full content of the post is displayed.

## Important Code Files

1. **urls.py** - This file in the `posts` app configures the URL patterns for the blog application, mapping them to the corresponding views.

2. **views.py** - The `views.py` file in the `posts` app contains the logic for rendering the blog post views. It includes the `index` view for listing all blog posts and the `post` view for displaying an individual post.

3. **models.py** - The `models.py` file in the `posts` app defines the `Post` model, which represents a blog post and includes fields such as `title`, `body`, and `created_at`.

4. **templates** - The `templates` directory contains the HTML templates used for rendering the views. The `index.html` template renders the list of blog posts, and the `post.html` template displays an individual post.

## Contributing

Contributions to this project are welcome. If you wish to contribute, please follow the guidelines mentioned in the `CONTRIBUTING.md` file.

## Known Issues or Limitations

Currently, there are no known issues or limitations with this project.

Please feel free to customize this documentation according to your requirements and add any additional sections or information you deem necessary.

If you have any further questions or need additional assistance, please let me know!

   
