**Techniques of Normalization**

     1) Minmax Scaling

     2) Mean Normalization

     3) Max Absolute Scaling

     4) Robust Scaling

**Min-Max Scaling**

--> min max scaling is the normalization technique.

--> min max scaling is used to transform the column and by extraction the minimum value and maximum value from the input column.

--> to calculate the minmax scaling formula is.

              Xi'=Xi-Xmin/Xmax-Xmin

--> Whenever we apply minmax scaling on the data then the data squizzes and ranges the value from [0,1].

--> Whenever we get an input data value with zero then the value ranges to be zero else it ranges one.

**Mean Normalization**

--> Mean Normalization is used to transfer the columns and also extract the minimum , maximum, and mean value

--> To calculate the mean normalization formula is 

             xi'=Xi-Xmean/Xmax-Xmin

--> The range of Xi-Xmean will be ranges from -1 to 1.

--> If val is less than mean will get a negative number.

--> If value is more than mean will get a positive number.

--> In the terms of geometric intution the data will be squizzed and become mean centric.

--> It is used to train in the ML Models to get a centered data.

--> Instead of using centered data we use standardization to train the dataset.

**Max-Absolute Scaling**

--> Max Absolute Scaling is used to train on the sparse data 

--> sparse data means the data which contains zeroes.

--> To calculate the Max Absolute Scaling formula is 

                      Xi'=Xi/|Xmax|

--> Max Absolute Scaling is Present in Scikit library.

**Robust Scaling**

--> Robust Scaling is used when the data contains outliers.

--> To calculate the Robust Scaling the formula is 

            Xi'=Xi-Xmeadian/(IQR) Inter quartile Range

--> Robust Scaler class is present in scikit module.
 
  
