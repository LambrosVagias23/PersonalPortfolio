# PersonalPortfolio
This is Lambros Vagias portfolio. Please read the README.file to understand the scope of each code file.



-------------------------------          ETL Script Assignment
ETL Script Assignment
Introduction
As part of this assignment, you are required to create an ETL (Extract, Transform, Load) script using any programming language of your choice. The script should fetch data from a dataset, perform necessary transformations, and generate a file in JSON format with the required fields.

Task Overview
The ETL process should:

Extract data from https://electrokinisi.yme.gov.gr/public/HelpMyfah/PublicData/. Specifically the "static" dataset.
Transform the extracted data to derive relevant fields.
Create and store the transformed data into a json file.
Requirements
The final output should include the following fields:

Count of unique Party IDs ("party_id")
Total number of locations per Party ID
Unique Power Type values found in the whole dataset ("power_type")
Date and time of the retrieved file (as displayed in the filename on the website)
sample output
{ "party_ids_count": 20, "total_locations_per_party_id": [ { "party_id": "XXX", "locations": 12 }, { "party_id": "ZZZ", "locations": 100 } ], "unique_power_types": [ "x", "y", "z" ], "retrieved_at": "01.01.2025 - 04:37:54" }

Deliverables
A script implementing the ETL pipeline.
The generated file as output.
A README file with instructions on how to run the script, the process you followed, possible issues or comments, etc..
Notes
You may use any language/library/framework familiar to you.
Clean code with appropriate comments is expected.
Exception handling is optional but will be highly appreciated!
Dependencies, if any, should be documented in the README.
This dataset is publicly available and maintained by the Ministry of Transportation, updated every day, and may occasionally be unavailable for short periods. If so, you may use the file dataset.zip from the repository.
Total duration of the assignment should not be more than 2 hours. In any case, we encourage you to commit the progress you have made within this timeframe, and we will discuss any leftovers in a follow-up call with you!
Bonus
Scrape the dataset URL and data file directly from the webpage! (e.g., using BeautifulSoup for Python)
Commit and push the deliverables in this git repository (OR provide a link to your favorite public git repo)
Good luck!
