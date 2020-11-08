# Healthcare Data Science
## Project: Healthcare Survey Responses

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

### Run

In a terminal or command window, navigate to the top-level project directory that contains this README and run the following commands:

```bash
jupyter notebook Healthcare_Survey_Responses.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data

**Features**
- review_id: unique identifier for each patient-submitted review of a provider at a given practice
- review_date: date the review was submitted
- rating: number of stars given to the provider in the review; stars range from 1-5, with 5 being high, no stars given = 0
- practice_id: unique identifier for each healthcare practice
- n_providers: number of providers working at a practice
- n_providers_surveys: At some practices, not all providers choose to send surveys to their patients. Thus, this field is less than or equal to n_providers.
- version: which version of the “long” survey a practice chooses (v1 or v2)	
- short_start_date: date a practice joins PatientPop and begins sending the “short” survey to its patients
- long_start_date: date on which a practice begins sending the “long” survey to its patients. This will be 6 mos after joining PatientPop.
- tech_type: Code for the electronic health records system used by each practice. The type of system used allows different levels of integration with PatientPop’s tools.
- specialty: primary specialty of a practice (e.g., internal medicine, dermatology, pediatrics, general dentist)
- zip: practice headquarters location
- city: practice headquarters location
- state: practice headquarters location
