# Canvas Course Enrollment Data Retrieval and Analysis using API
## Overview
This repository contains a Python script for retrieving enrollment data from the Canvas API for a specific course and organizing it into a CSV file. The script utilizes the Canvas API to fetch enrollment details, including user information, roles, last activity, and grades.

## Features
<strong>Enrollment Data Retrieval:<strong/> The script makes use of Canvas API to fetch enrollment data for a specified course.

<strong> Data Organization: <strong/> Extracted data is organized into a structured DataFrame and saved as a CSV file for easy analysis.

<strong> Data Analysis: <strong/> The script extracts key information such as user ID, user role, last activity, grades, and more for in-depth analysis.

## Dependencies
Python 3.x

requests

pandas

## Usage
Clone the repository:
git clone https://github.com/GopiChandYenikapalli/Canvas-API-Enrollment-Data-Retrieval-and-Analysis.git

Install dependencies:
pip install -r requirements.txt
#### Replace Your Access token key in the script with your actual Canvas API access token.

Modify the course_id variable to the desired Canvas course ID.
Run the script:
python canvas_enrollment_analysis.py

The script will fetch the data, organize it, and save it to a CSV file #### (enrollments_course_id.csv).

## Configuration
Make sure to replace the Your Access token key with a valid Canvas API access token. If you don't have one, follow the Canvas API documentation to obtain it.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

This script was developed for educational and demonstrational purposes.

Canvas API documentation: Canvas LMS API
