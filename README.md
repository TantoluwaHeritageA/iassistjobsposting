# Description
This project was meant to scrape data from the page: iassit, clean and analyze the data and interpret it visually for research purposes

# Overview 

The goal of this project was to extract and analyze job advertisements for research data librarians from the IASSIST online job repository over a five-year period. It focused on identifying trends in job postings, including core responsibilities, required qualifications, and relevant skills.

The extracted data included:

* Job Title 
* Employer 
* Employer URL
* Posted Date
* Salary 
* Job Location
* Education/Experience
* Qualification
* Skills
* Source URL

# Output

A visual representation showing how the extracted data correlated and related to one another was created and presented at a conference in Ghana for a research publication.

## Project Duration

2.5  months

## Challenges faced while extracting the data 

Main website url  - https://iassistdata.org/jobs-repository/

* To view individual job postings, it was necessary to navigate from the main jobs repository page to separate URLs for each job posting. On the job details page, all elements were wrapped inside a single <div> element. Each piece of information was structured inconsistently using tags such as "strong", "h2", and "p".

For Example, this image below, in the section title "Description" , there is more information about the job, but description and the text do not have a main section element bounding them together. 


<img width="1156" height="649" alt="image" src="https://github.com/user-attachments/assets/c9161488-4fca-499a-ac28-95b4022e51de" />



* Some job postings contained fields such as Description, Salary, or Location, while others did not.
  
* Although some data was successfully extracted, several fields returned null values because the HTML structure varied across different job postings.

## Language

The project was originally developed in [Google Colab](https://colab.research.google.com/drive/1eEyOs6d8hWkX-BZ2KYRWpeJoVShEDoIM) using Jupyter Notebook, python and assistance from ChatGPT to support the data extraction process and structure the extracted data according to the project objectives.

