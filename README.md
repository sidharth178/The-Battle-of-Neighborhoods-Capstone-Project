# THE-BATTLE-OF-THE-NEIGHBOURHOODS-PROJECT

<img src="Readme Images/ibm capstone logo.png" style="width:800px;height:300px;">

## 📌**Objective**

The objective of this project is to create a prefect place detection tool which'll find the best neighbourhood or place to open a start up or restaurant using Foursquare API. In this project we'll take Italian Restaurant as an example.That is we'll find the best place or neighborhood to open an Italian restaurant in Toronto(A city in Canada) using Foursquere location data.
### 👪**Target Audiance**

* Business personnel who wants to invest or open a start up company or restaurant.
* Bachelors who want to stay in a good city where they can get each facilities what they want like GYM,Playground,Parlour,Movie theatre etc.
* The freelancer who loves to have their own small company or restaurant as a side business.
* Marketing companies who want to release a new product on a best place.
* Researchers who want to create a camp for Survey.
* Torrists who wants to eat italian food.

## 📁 **Data Description**
For this project we need these following data:
1. ***Toronto City data that contains Borough, Neighborhoods along with there latitudes and longitudes***
* **Data Source:** https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M
* **Description:** This Wikipedia page contain all the information we need to explore and cluster the neighborhoods in Toronto. We will be required to scrape the Wikipedia page and wrangle the data, clean it, and then read it into a pandas dataframe so that it is in a structured format like the Toronto dataset.
2. ***Geographical Location data using Geocoder Package***
* **Data Source:** https://cocl.us/Geospatial_data
* **Description:** The second source of data provided us with the Geographical coordinates of the neighbourhoods with the respective Postal Codes.
3. ***Venue Data using Foursquare API***
* **Data Source:** https://foursquare.com/developers/apps
* **Description:** From Foursquare API we can get the name,category,latitude,longitude for each venue.

## 🔑**Prerequisites**
All the required libraries are included in the file <code>requirements.txt</code>

## ⚠️**TechStack/framework used**
- Machine Learning
- Web Scraping
- Foursquare API
- Geocoder
- Beautiful Soup
- Folium

## 🚀**Installation**
Step-1: 
```
# Fork this repository or else use git clone, to clone the repository on your local machine.
$ git clone https://github.com/sidharth178/The-Battle-of-Neighborhoods-Capstone-Project.git
```
Step-2:(Recommended)
```
# Otherwise, In "The_Battle_Of_Neighborhoods.ipynb" file,there is a link in the begining to open the file in Google Colab. Click in that link.
```
Step-3: 
```
# If you are following the "Step 1", Install the requirments.txt file else if you'r following "Step 2", no need to install anything.
$ !pip install -r requirements.txt
```
Step-4: 
```
# Open the code in any code editor like Jupyter Notebook, Google Colab(Recommended)
```
Step-5:
```
# Run the code
```


📌 In this capstone project we are going to answer of these following major steps:

* **Assignment-1:** Scrape the data from the wikipedia page of Toronto.

* **Assignment-2:**  Get the geographical coordinates of the neighborhoods using the Geocoder package.

* **Assignment-3:** Explore and cluster the neighborhoods in Toronto.

### ⌛Clustered Neighborhoods
<img src="Readme Images/Clustered_neighborhood.png" style="width:800px;height:300px;">

### 📝**Blog Post(Medium)**
 For more details about the implementation of this project,i've written a blog on Medium. Check [here](https://sidharth178.medium.com/the-battle-of-neighborhoods-f3f8bff9abf3) blog.
 
## ❤️**Owner**
Made With ❤️ by [Sidharth kumar mohanty](www.linkedin.com/in/sidharth178)

## 😖Troubleshoot
Any issues??? Feel free to ask.[Linkedin](www.linkedin.com/in/sidharth178)

If you find this repo useful,don't forget to give a ⭐

Thanks! ❤️
