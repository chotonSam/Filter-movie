This web application is created using create-react-app

I found the data from "The Movie Database API".
I fetched the data using Fetch API. In this data, every element has a genre id that defines the genre category. I filter the data using this I'd.

the main parent component of this application is App.js. Where I fetched the data. then there is two child component under the App.js component. one is Filter.js and another is Movie.js

in filter.js I code the filter functionality. in every button click I set a number in a state. so I can compare the number with the genre id. and then I can separate the data using the array filter method. 

and in Movie.js we show the data.

and we pass the data parent to the child component using react prop drilling.


Deploy link# https://legendary-bavarois-ca269c.netlify.app/
