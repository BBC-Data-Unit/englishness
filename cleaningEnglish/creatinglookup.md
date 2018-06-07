# Creating a lookup for misspelt areas (the YouGov Englishness survey)

Many names of towns, cities and regions are misspelt, making it hard to properly count those mentioned most often.

To solve this, we created a lookup table which would allow us to convert misspelt areas into their proper equivalents. Here are the steps we followed:

1. Use R to split the column into single words. This gave us a list of every term used.
2. Use Open Refine to duplicate that column and then clean it using the 'cluster and edit' feature. This converts similar spellings to clean versions. Now we have a table with two columns: a mixed clean/unclean one, and a clean one.
