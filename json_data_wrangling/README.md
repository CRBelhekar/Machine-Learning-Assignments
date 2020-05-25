# Data Wrangling - JSON
Collection of exercises wrangling a JSON file of projects funded by the World Bank.

<br>

---
### USING DATA IN THE FILE  `world_bank_projects.json`:
* Find the 10 countries with the most projects.


* Find the top 10 major project themes (using column `mjtheme_namecode`).


* For some entries in the exercise above, the name is missing. Create a dataframe filling in the missing names.

<br>

1. **Import Packages, Load JSON file as a Dataframe, Inspect** - Get a look at the state and structure of the dataset. Inspect the columns needed for the exercises.

2. **Find the 10 Countries with the Most Projects** - Retrieve a value count of country names, which is sorted in descending order; save the first 10 results.

3. **Load JSON file as a String, Flatten, Inspect** - The column needed to finish the exercises contains nested data, so it needs to be normalized.

4. **Find the Top 10 Major Project Themes** - This is accomplished by a value count of project codes since names are known to be missing.

5. **Create a Dataframe Filling in the Missing Names** - Sort the dataframe, fill empty cells with NULL values, then replace those by backfilling.

6. **Find the Top 10 Major Project Themes by Theme Name** - Produce a more descriptive list of top projects by getting a value count of project names.

<br>
