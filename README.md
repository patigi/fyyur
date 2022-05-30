# fyyur
Fyyur - Artist Booking App

Introduction
Fyyur is a musical venue and artist booking site that facilitates the discovery and bookings of shows between local performing artists and venues. This site lets you list new artists and venues, discover them, and list shows with artists as a venue owner.

Your job is to build out the data models to power the API endpoints for the Fyyur site by connecting to a PostgreSQL database for storing, querying, and creating information about artists and venues on Fyyur.
Development Setup

    Initialize and activate a virtualenv using:

python -m virtualenv env
source env/bin/activate

    Install the dependencies:

pip install -r requirements.txt

    Run the development server:

export FLASK_APP=myapp
export FLASK_ENV=development # enables debug mode
python3 app.py

    Verify on the Browser
    Navigate to project homepage http://127.0.0.1:5000/
