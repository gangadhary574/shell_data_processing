#  shell-data-processing

### Acquiring data from Url

- Use ```curl ``` command to extract data from a wesbite. Using ``` curl <website url>  -O <filename.format> ``` to extract the url data into the required file format. 

### Process text data
- ```tr ' ' '\12' < returnedfile``` is used to transform space in the data file.
- ```tr ' ' '\12' < returnedfile | sort``` is used for sorting.
- ``` tr ' ' '\12' < returnedfile | sort | uniq -c | sort -nr > result.txt``` is used to transfer of shift processed data into a result.txt file.
-  ```-n``` -- is used to sort value by their numerical values.
- ```-r``` -- is used to reverse the comparisions. 
- A single letter flag has a single dash.
- Two dashes are used for multiple letter flags. 

#### Important bash commands
- use ```CTRL+SHFT+C``` is paste into bash instaead of ```CTRL+C```.







