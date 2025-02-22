# flasklab8
# flasklab8
FitZone Fitness Website
Project Overview
FitZone Fitness is a website project designed to promote health and fitness. It consists of three main pages (Home, About Us, and Membership) and uses Flask for backend functionality. The project includes static assets like images and CSS for styling.

File Structure
arduino
Copy code
LAB 6 ITC/
├── static/
│   ├── gym12.jpg
│   ├── gym11.jpg
│   ├── gym33.jpg
│   ├── gym55.webp
│   ├── gym111.jpg
│   ├── gym123.jpg
│   ├── gym222.jpg
│   ├── logo.png
│   └── styles.css
├── templates/
│   ├── about.html
│   ├── home.html
│   ├── membership.html
├── app.py
└── README.md
Description of Files
Templates
home.html: The homepage showcasing the gym’s introduction, promotional content, and call-to-action buttons.
about.html: Provides detailed information about the gym’s mission, vision, and services.
membership.html: Contains details about membership plans and includes a login or signup form.
Static Files
Images:
gym12.jpg, gym11.jpg, gym33.jpg, gym55.webp, gym111.jpg, gym123.jpg, gym222.jpg: Images used for various sections of the website.
logo.png: Gym logo for branding.
CSS (styles.css): Contains the styles and layout for all the HTML pages, ensuring a cohesive design.
How to Run
Clone the repository to your local machine:

bash
Copy code
git clone <repository_url>
Navigate to the project directory:

bash
Copy code
cd LAB 6 ITC
Make sure Python is installed. Then install Flask if it’s not already installed:

bash
Copy code
pip install flask
Run the Flask application:

bash
Copy code
python app.py
Open your browser and visit:

arduino
Copy code
http://127.0.0.1:5000
Features
Responsive Design:
Pages adjust for different screen sizes, ensuring usability on mobile and desktop devices.
Three Core Pages:
Home: Overview and promotional section.
About Us: Explains the gym’s purpose and services.
Membership: Information about joining and managing memberships.
Static Resources:
High-quality images and a consistent styling theme.
Technologies Used
Frontend: HTML, CSS
Backend: Python, Flask
Static Assets: Images and styles for visual appeal