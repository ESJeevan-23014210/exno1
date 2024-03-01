# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output

```py
# Developed By: Jeevan E S
# Register Number: 212223230091
```
<table>
  <tr>
    <td width=50%>


### 1) Read and display DataFrame
```Python
import pandas as pd
df=pd.read_csv('/content/SAMPLEIDS.csv')
df
```
  </td>
  <td>
              
#### OUTPUT:

![1](https://github.com/ESJeevan-23014210/exno1/assets/147139456/995a7ca9-6fc4-4259-b568-cb81ea2cee57)

</td>
</tr>
<tr>
  <td width=50%>
              
### 2) Display head
```Python
df.head()
```
  </td>
  <td>
              
#### OUTPUT:

![2](https://github.com/ESJeevan-23014210/exno1/assets/147139456/f32c4ee6-7fa3-44cf-ae63-c7af41b6325b)


</td>
</tr>
<tr>
  <td width=50%>

### 3) Display tail
```Python
df.tail()
```
  </td>
  <td>
              
#### OUTPUT:

![3](https://github.com/ESJeevan-23014210/exno1/assets/147139456/e88900da-26c5-4933-9508-3d8454f66a4d)


</td>
</tr>
<tr>
  <td width=50%>

### 4) Info of datafram
```Python
df.info()
```
  </td>
  <td>
              
#### OUTPUT:

![4](https://github.com/ESJeevan-23014210/exno1/assets/147139456/e25c7ff7-8345-40e2-a01a-fb6192df1d23)


</td>
</tr>
<tr>
  <td width=50%>

### 5) Describe about the dataframe
```Python
df.describe()
```
  </td>
  <td>
              
#### OUTPUT:

![5](https://github.com/ESJeevan-23014210/exno1/assets/147139456/7e03013e-9979-46c4-8418-5d7dd029d95f)

</td>
</tr>
<tr>
  <td width=50%>

### 6) Shape of the datafram
```Python
df.shape
```
  </td>
  <td>
              
#### OUTPUT:

![6](https://github.com/ESJeevan-23014210/exno1/assets/147139456/56b6dc0c-b29c-43a2-9781-60144cad1ef8)


</td>
</tr>
<tr>
  <td width=50%>

### 7) Checking tha NUll values
```Python
df.isnull()
```
  </td>
  <td>
              
#### OUTPUT:

![7](https://github.com/ESJeevan-23014210/exno1/assets/147139456/85a30379-bcaf-4edd-b3a6-0beca1f6273e)


</td>
</tr>
<tr>
  <td width=50%>

### 8) Drop the Null values
```Python
df.dropna(axis=0)
```
  </td>
  <td>
              
#### OUTPUT:

![8](https://github.com/ESJeevan-23014210/exno1/assets/147139456/2bcb796a-4d3a-4540-a801-f43356c61767)


</td>
</tr>
<tr>
  <td width=50%>



### 9) Fill the Null values
```Python
df.fillna(0)
```
  </td>
  <td>
              
#### OUTPUT:

![9](https://github.com/ESJeevan-23014210/exno1/assets/147139456/c6972daa-0cbd-4b24-b6e1-0ac4da52f27d)


</td>
</tr>
<tr>
  <td width=50%>

# Result
The data cleaning has beeen done successfully.
