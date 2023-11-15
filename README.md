

# Django-Google-API

## Overview

Django-Google-API is a Django project designed to leverage various Google APIs for functionalities such as auto-populating fields, displaying maps, and generating routes for multiple waypoints.

## Getting Started

1. Navigate to your development directory:

   ```bash
   cd path/to/your/development/directory
   ```

2. Create a virtual environment:

   ```bash
   mkvirtualenv did_django_google_api_tutorial
   ```

3. Create a new project directory:

   ```bash
   mkdir did_django_google_api_tutorial
   ```

4. Clone the repository into the new directory:

   ```bash
   git clone https://github.com/mangesh123vispute/Django-google-api.git
   ```

5. Install project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Create and update `settings.ini` with your Google API information:

   ```ini
   # settings.ini

   GOOGLE_API_KEY = ""
   RECAPTCHA_PUBLIC_KEY = ""
   RECAPTCHA_PRIVATE_KEY = ""
   ```

7. Apply migrations:

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

8. Run the development server:

   ```bash
   python manage.py runserver
   ```

9. Access the application at https://django-google-api.onrender.com

## Important Note

Don't forget to activate the following Google APIs in your Google Cloud Console:

- reCAPTCHA
- Places API
- Maps Javascript API
- Directions API
- Distance Matrix API
- Geocoding API

## Additional Notes

- Ensure to replace the placeholders in `settings.ini` with your actual API keys.
- The project utilizes Google APIs for features like auto-populating fields and displaying maps.
- Migrations are essential for updating the database structure.
- Visit [https://django-google-api.onrender.com](https://google-api-django.vercel.app/)https://google-api-django.vercel.app/ to view the application.


