AI Blog Generator
Overview
AI Blog Generator is a Django-based web application that generates blog content from YouTube videos. It uses Bootstrap for the frontend. By providing a YouTube video link, the application downloads the audio, processes it using ChatGPT to generate a blog, and saves the result.

Features
User-friendly interface built with Bootstrap
Accepts YouTube video links to download audio
Utilizes ChatGPT for blog content generation
Stores generated blogs for future access
Technologies Used
Django: Backend framework
Bootstrap: Frontend framework for responsive design
pytube/yt-dlp: Libraries for downloading YouTube video/audio
ChatGPT: For generating blog content
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/ai-blog-generator.git
cd ai-blog-generator
Create a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Set up the Django project:

bash
Copy code
python manage.py makemigrations
python manage.py migrate
Run the development server:

bash
Copy code
python manage.py runserver
Access the application:

Open your web browser and go to http://127.0.0.1:8000.

Configuration
ChatGPT API Key:

Ensure you have an API key for ChatGPT. Set the API key in your environment variables or in the Django settings file.

YouTube Audio Download:

The application uses pytube or yt-dlp for downloading audio from YouTube. Ensure you have these libraries installed.

Usage
Home Page:

Enter the YouTube video link in the provided input field.
Click on the "Generate Blog" button.
Blog Generation:

The application will download the audio from the provided YouTube link.
The audio will be processed by ChatGPT to generate a blog.
The generated blog will be displayed and saved for future access.
Contributing
Fork the repository.

Create a new branch:

bash
Copy code
git checkout -b my-feature-branch
Make your changes and commit them:

bash
Copy code
git commit -m "Add some feature"
Push to the branch:

bash
Copy code
git push origin my-feature-branch
Create a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contact
For any questions or feedback, please contact awaisjutt512@gmail.com.

