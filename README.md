Health Blog Platform

 Description

This Django application is a health blog platform where users can read and contribute articles on various health topics. It provides functionalities for user registration, authentication, article submission, and commenting.
Features

- User registration and authentication
- Browse and read articles
- Submit comments on articles
- Submit new articles (authenticated users only)
- Form validation for article submission

Setup Instructions

1. Clone the repository:

   
   git clone https://github.com/ Pruthvik-P/health-blog.git
   

2. Navigate to the project directory:

   
   cd health-blog
   

3. Install dependencies:

   
   pip install -r requirements.txt
   

4. Run database migrations:

   
   python manage.py migrate
   

5. Start the development server:

   
   python manage.py runserver
   

6. Access the application at http://localhost:192.168.1.12/
Usage

- Register a new account or log in with existing credentials to access the full functionality of the platform.
- Browse articles on various health topics.
- Click on an article to read its full content and view comments.
- Leave comments on articles to share your thoughts or ask questions.
- Authenticated users can submit new articles through the "Submit Article" feature.

Technologies Used

- Django
- HTML
- CSS
- JavaScript
