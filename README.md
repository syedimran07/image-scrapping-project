# Image Scraper Project
This is a Flask application that scrapes images from Google based on a user's search query and stores the images locally and in a MongoDB database.

## Tech Stack
- Python 3.x
- Flask
- MongoDB
- BeautifulSoup (bs4)
- Requests
- Flask-CORS
- Logging

  
## Environment Variables
Create a .env file in the project directory and add the following variables:

- MONGO_URI=<your_mongodb_connection_string>
Replace <your_mongodb_connection_string> with your actual MongoDB connection URI.


## Install Dependencies
Run the following command to install the necessary dependencies:

- pip install -r requirements.txt


## API Base URL
The API is configured to run on: http://0.0.0.0:80

Available Endpoints:

- GET /: Displays the homepage where the user can enter a search query.
- POST /review: Accepts a search query, scrapes images from Google, saves them locally, and stores the image data in MongoDB.


## License
This project is licensed under the MIT License.
