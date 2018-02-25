# Twitter API

Twitter streaming API for streaming data and store in .csv form and adding some filters. The whole project is divided in 3 modules. 


## Twitter Streaming API

First API, streams twitter data based on a particular word given by the user for example "Nirav Modi". The whole data is stored in the file streamed_data.csv.

## Filter and search stored tweets

API-2 filteres tweets based on username, screen name, retweet count, favourite count, language, location, created_date.

## Export filtered data into CSV file

API-3 exports the above filtered result into CSV file. Here user can give filename according to his choice. Default file name is 'output.csv'. 

### Technology Used

 - Python
 - Tweepy Library
 - Json Parser


### Instructions

 1. Clone the project
 2. cd into the current project directory
 3. open jupyter-notebook
 4. open the file named `BackEnd_TwitterStreaming_AbhayGarg.ipynb`
 **5. API to trigger twitter stream and store it in json form**![enter image description here](https://raw.githubusercontent.com/gargabhay1999/TwitterStreaming/master/Images/Screenshot%20from%202018-02-25%2023-34-28.png)
 
 6. Tweet Details in json format![enter image description here](https://raw.githubusercontent.com/gargabhay1999/TwitterStreaming/master/Images/Screenshot%20from%202018-02-25%2023-34-46.png)

7. User Details in Json Format![enter image description here](https://raw.githubusercontent.com/gargabhay1999/TwitterStreaming/master/Images/Screenshot%20from%202018-02-25%2023-34-51.png)

8. Streamed Data File![enter image description here](https://raw.githubusercontent.com/gargabhay1999/TwitterStreaming/master/Images/Screenshot%20from%202018-02-25%2023-34-56.png)

9. User_access_type Graph for whole data-set![enter image description here](https://raw.githubusercontent.com/gargabhay1999/TwitterStreaming/master/Images/Screenshot%20from%202018-02-25%2023-36-10.png)

**10. API-2 to filter tweets based on parameters** ![enter image description here](https://raw.githubusercontent.com/gargabhay1999/TwitterStreaming/master/Images/Screenshot%20from%202018-02-25%2023-36-40.png)

11. Output of filtered Data![enter image description here](https://raw.githubusercontent.com/gargabhay1999/TwitterStreaming/master/Images/Screenshot%20from%202018-02-25%2023-36-45.png)

**12. API-3 Returns a CSV response of the filtered tweets. Filters are same as in second API.** ![enter image description here](https://raw.githubusercontent.com/gargabhay1999/TwitterStreaming/master/Images/Screenshot%20from%202018-02-25%2023-37-04.png)

13. User_access_type Graph for filtered data-set![enter image description here](https://raw.githubusercontent.com/gargabhay1999/TwitterStreaming/master/Images/Screenshot%20from%202018-02-25%2023-37-09.png)

