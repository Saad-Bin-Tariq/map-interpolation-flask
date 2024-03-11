# Flask API for Interpolating Point Data with Temperature Values

This repository contains a Flask API for interpolating point data with temperature values using Python libraries such as NumPy, SciPy, and Shapely. The API provides endpoints to receive input point data along with temperature values and returns interpolated temperature values for specified locations.

## Features

- **Flask API:** Utilizes the Flask framework to create a lightweight web API for handling HTTP requests and responses.
- **Interpolation:** Implements interpolation algorithms using NumPy and SciPy to predict temperature values at specified locations based on the provided point data.
- **GeoSpatial Support:** Incorporates Shapely to handle geometric operations, enabling the processing of spatial data such as polygons for defining the area of interest.

## Key Components

- **app.py:** Main Flask application file defining the API endpoints and request handling logic.
- **interpolation.py:** Module containing functions for interpolating temperature values using point data.
- **requirements.txt:** List of Python dependencies required for running the Flask API.

## Usage

1. Clone the repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the Flask application using `python app.py`.
4. Send HTTP requests to the API endpoints to interpolate temperature values for specified locations.

## Contributing

Contributions to this project are welcome! If you have any ideas for improvements or new features, feel free to open an issue or submit a pull request.

