How to run this script?
1-Upload data to your Hadoop file system in the files view
2-Make a new script and the code to script in the Pig view
3-Add the path to the uploaded dataset and execute the script



1-The order.csv should be uploaded in this case it is uploaded to /user/maria_dev/orders.csv
2-The first step is to upload the data with the seprator ,
3-Second step is to define the target in this case "Holland". This means all rows are not including the target are filtered out
4-Third step is counting how many times the target is coming back for each location
5-Fourth step is adding the location and count that it belongs to it
6-Sixth step is ordering the array alphabetically
7-Finally is printing the result 