# Big-Data-Tools-Techniques-Project-using-Data-Frame
Cleaning the excell file using DATA Frame and answering the question

The data necessary for this assignment will be zipped CSV files. The .csv files have a header describing the files’ contents. They are:

Clinicaltrial_2023.csv: Every row in the dataset corresponds to an individual clinical trial and is identified by different variables. It's important to note that the first column contains a mixture of various variables separated by a delimiter, and the date columns exhibit various formats. Please consider these issues and ensure that the dataset is appropriately prepared before initiating any analysis. (Source: ClinicalTrials.gov)
pharma.csv: The file contains a small number of a publicly available list of pharmaceutical violations. For the purposes of this work, we are interested in the second column, Parent Company, which contains the name of the pharmaceutical company in question. (Source: https://violationtracker.goodjobsfirst.org/industry/pharmaceuticals)
client wishes to gain further insight into clinical trials. You are tasked with answering these questions, using visualisations where these would support your conclusions. You should address the following questions.

The number of studies in the dataset. You must ensure that you explicitly check distinct studies.
You should list all the types (as contained in the Type column) of studies in the dataset along with the frequencies of each type. These should be ordered from most frequent to least frequent.
The top 5 conditions (from Conditions) with their frequencies.
Find the 10 most common sponsors that are not pharmaceutical companies, along with the number of clinical trials they have sponsored. Hint: For a basic implementation, you can assume that the Parent Company column contains all possible pharmaceutical companies.
Plot number of completed studies for each month in 2023. You need to include your visualization as well as a table of all the values you have plotted for each month.
