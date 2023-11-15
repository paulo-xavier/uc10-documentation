![Python image](https://github.com/paulo-xavier/uc10-documentation/blob/main/assets/python.png)

# 🐍 Python code 

<br>

 ## Table of contents
- [Explananation about the code](#explanation-abut-the-code-involving-excel-and-python)

<br>

## Explanation abut the code involving excel and python

<div align="center">
  
```
import pandas as pd

df = pd.read_excel("base.xlsx") 

df['Average'] = df[['Grade1', 'Grade2', 'Grade3']].mean(axis=1)

df.to_excel('grade_student.xlsx', index=False)
```
</div>
<br>

 In this code example, we are working with a excel spreadsheet called `base.xlsx`. This spreadsheet contains the following data: 
 <br><br>

<div align="center">
 <img src = "https://github.com/paulo-xavier/uc10-documentation/blob/main/assets/excel1.png" width="550px" height="150px">
</div>
<br>
As we can see, this spreadsheet contains a list of students and their respective grades. However, a column with the average of their grades is missing. To avoid the process of making the average manually, we are going to create a python code for that. 
In the first line we improt a package called <code>pandas</code>. This package will allow us to read the <code>.csv</code> file and generate a new file based on that. 

 <br>

> <p align="center"> <code>import pandas as pd </code> </p>

<br>

In the next line, we will read the file `base.xlsx` that contains our excel spreadsheet:
<br> <br>

> <p align = "center" > <code> df = pd.read_excel("base.xlsx")</code>  </p>
<br>

Finally, in this code snippet we will generate a new column, named `average` which is the sum of the 3 grades divided by 3. Python automatically will calculate the grade average for each row and will assign the result in a new column called `average`.   

<br>

> <p align = "center" > <code> df['Average'] = df[['Grade1', 'Grade2', 'Grade3']].mean(axis=1) </code>  </p>

<br>
Then, Python will generate a new CSV file containing the column `average`. This new file is named `grade_student.xlsx`. 

<br>

> <p align= "center"> <code> df.to_excel('grade_student.xlsx', index=False) </code> </p>

<br>
<div align="center">
<img src = "https://github.com/paulo-xavier/uc10-documentation/blob/main/assets/excel2.png" width ="550px" height ="150px">
</div>
