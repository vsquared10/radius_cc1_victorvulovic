# Radius Data Science Coding Challenge 1: Data Analysis

This challenge will test your ability to examine data sets and compute some basic properties that we find generally 
useful. The file [here](data.json.zip) contains a list of businesses which are fairly representative of data we get from our external data providers. 
Each business has the following fields:

- **name**: The name of the business
- **address**: The street address of the business
- **city**: The city the business is in
- **zip**: The businesses zip code
- **time_in_business**: The years the company has been in business
- **phone**: The businesses phone number
- **category_code**: The [NAICS](https://classcodes.com/naics-code-list/) code for the business
- **headcount**: The number of people employed by the business
- **revenue**: The revenue (in thousands) of the business

Use this data, and whatever programming language you like (we use python) to calculate the following:

1. **Fill Rate**: For each field, how many records have a value.
2. **True-Valued Fill Rate**: For each field, how many records have *relevant* data in them. For example, a field which
has string valued entries may have elements that contain something like `' '`. This is a string but may not be
'good' data depending on the field.
3. **Cardinality**: The cardinality of each field.
4. **Something interesting**: Find something cool or odd in the data set and tell us about it.

Your deliverable will be a report with your results and a github repo with your code. For the report, imagine that you 
are creating a research paper that will be delivered to stakeholders -- it should be more than just a series of answers,
explain your process and tell a story with the data. Also, please **_do not_** check the data set into your repo. Just 
the report and the code please!

If you run into any problems, or you have any questions, please don't hesitate to contact us.

**Good luck!**