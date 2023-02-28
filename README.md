# 1913072_RitwijaDixit_DMW_Assg1
## Apriori Algorithm

This is a simple implementation of Apriori Algorithm in Python. It takes in a csv file with a list of transactions, and results out the most frequent itemsets. The values for minimum_support should be given from the user at the runtime.

### Input

The input format should be csv file in following format:

Bread,Milk <br>
Beer,Bread,Diaper,Eggs <br>
Milk,Diaper,Beer,Coke <br>
and so on..

For uploading csv file, We have used following method:

df=pd.read_csv(io.BytesIO(uploaded['dataset1.csv']),header=None)

Here, enter the csv file name in the method or rename the csv file name as dataset1.csv.

### Output
The output will show the most frequent itemsets from the given dataset.
### Submitted By: Ritwija Dixit
### Roll No: 1913072
