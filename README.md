Geolocation 

**********

Java based Application for entering the location and getting output on google Maps 

Converting an address in to latitude and longitude (and vice versa ) is very easy using Google's GeoCoding API. GeoCoding is the process to convert a simple address line like "123 GardenVille, YORKTOWN, USA" to latitude,longitude like "37.110458,-76.449844". Converting latitude,longitude to address is called Reverse GeoCoding.

You can get the output from geocoding api either in json or in xml format .

Here is the sample java program to Convert addresses in to latitude and longitude . I have used Jackson API to convert json response in java Objects , and apache commons IO to make Http calls to geocoding api . Download the Jars 
1)https://docs.google.com/file/d/0B6Jwcs3OgZiSVk00MHBEZzRLQzA/edit
2)https://docs.google.com/file/d/0B6Jwcs3OgZiSeGxMdUV4SGlld0E/edit
3)https://docs.google.com/file/d/0B6Jwcs3OgZiSbHBTZ3ZSandodDQ/edit

Input address can be in "address ,city ,state ,country ,zip code" form .

Once the address is inputed from the code while initializing the object, it calls the method to convert it to lat/longitude and than it is passed to display method of Google Maps demo class to display the location using google maps which is embedded in swing.

Test Coverage is being tested using :-

1) ECLEMMA it is a tool which is being integrated in eclipse which triggers and test the code coverage for the code which is run as Java application.

2) Snapshot of code coverage is being attached as Code -Coverage. Kindly have a view of it to get a glimse of code coverage.


