1. # MpPulse - News Aggregator

Demo link - https://jayeshmahawer.github.io/django-news-website/
## Overview
MpPulse is a Django-based web application that aggregates news articles from various sources, specifically focusing on technology news from TechCrunch. The application provides a user-friendly interface to display the latest news articles along with their descriptions and images.

## Features
- Fetches top headlines from TechCrunch using the News API.
- Displays news articles with titles, descriptions, and images.
- Responsive design for optimal viewing on various devices.

## Technologies Used
- Django (Python web framework)
- HTML/CSS for front-end design
- Bootstrap for responsive layout
- News API for fetching news articles

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd MpPulse

2. Create a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows use`venv\Scripts\activate`

3.Install the required packages:
pip install -r requirements.txt

4. Set up the database:
python manage.py migrate

5. Run the development server:
python manage.py runserver

6. Open your browser and go to http://127.0.0.1:8000/ to view the application.

Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

License
This project is licensed under the MIT License - see the LICENSE file for details.

**Note:** Replace `<repository-url>` with the actual URL of your repository.
