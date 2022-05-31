# task1
### Goal : <br> 
Develop a code that can clean this dataset and extract Technical (Hard) skills. <br>
### steps: <br>
1- Explore raw data file. <br>
2- It contains only one column that contains categorical data. <br>
3- Search for duplicates and drop them improve speed in next steps. <br>
4- Exract tokens in each skill row to ignore stop words, puctuation. <br>
5- Drop duplicates again. <br>
6- Apply same preprocessing steps on a technical skills dataset extracted from EMSI API which provides 30,000+ skills ( technical and non technical) <br>
7- Extracting skills from the API steps are provided in Extract technical skills.ipynb file <br>
8- Now search for each skill in our preprocessed dataset if it is a substring in a skill from technical skills dataset. <br>
9- if it exists as a technical skill , keep it in a separate list (res). <br>
10- Now The final resuly contains 2338 skill. <br>

### Note:
soft skills could be found with the same methodology using emsi api but with "typeIds":"ST1" instead of "typeIds":"ST2" in the API query string <br>

