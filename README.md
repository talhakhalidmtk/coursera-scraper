# Coursera Scraper

This repository contains a Python script that utilizes Selenium to scrape data from Coursera. The script collects information about various courses and their details from Coursera's website.

## Scraped Fields

The script scrapes the following fields for each course:
1. Title: The title of the course.
2. Institute: The institution offering the course (if available).
3. Rating: The course rating.
4. Recent Views: The number of recent views for the course.
5. Students Enrolled: The number of students enrolled in the course.
6. Time Requirement: The approximate time required to complete the course.
7. Skills: A list of skills covered in the course.
8. Learner Count: The total number of learners who have taken the course.
9. Difficulty Level: The difficulty level of the course.
10. Duration: The duration of the course.
11. Sub-course: Additional information about the course or its sub-courses.

The scraped data is stored in a dictionary format for each course.

## Prerequisites
You can install the required Python packages by running the following command:
```bash
pip install coursera-scraper

from scraper.main import scraper

results = scraper(keyword='python')
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
