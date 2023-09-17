<h1 align="center">Choropleth Map GDP</h1>
</br>

<div align="center">
<img src="https://github.com/SidneyTeodoroJr/choropleth_map_GDP/blob/main/capita.png"    alt="choropleth map">
</div>
</br>
</br>


This Python script uses the Plotly Express library to create an animated choropleth map that displays the per capita Gross Domestic Product (GDP) of different countries over the years.
</br>

## 1 - Importing Libraries:

. `import plotly.express as px:` Imports the Plotly Express library, which is used to create interactive plots, including choropleth maps.

. `import pandas as pd:` Imports the Pandas library, which is used for data manipulation and analysis.
</br>

## 2 - Data Import:

The script reads data from a CSV file hosted on GitHub. The file contains data relating to GDP per capita for various countries over time, as well as information about the countries such as the ISO code and country name. The data is read into a Pandas DataFrame called `data`.
</br>

## 3 - Creation of the Choroplectic Map:

. `px.choropleth:` This Plotly Express function is used to create a coropleth map. 

. `data`: The DataFrame that contains the data.

. `locations`: The column in the DataFrame that contains ISO country codes, used to map geographic regions.

. `color`: The column in the DataFrame that contains the values ​​that determine the color of the map (in this case, GDP per capita).

. `hover_name`: The column in the DataFrame that provides additional information displayed when the mouse is placed over a region.

. `projection`: The geographic projection used for the map.

. `animation_frame`: The column in the DataFrame that determines the animation over time (in this case, the year).

. `title`: The title of the map.
</br>

## 4 - Layout Customization:

`fig.update_layout`: This line of code is used to update and customize the map layout. In this case, the map background color is set to light gray.
</br>

## 5 - Map Display:

`fig.show()`: Displays the interactive map on the screen.
</br>
</br>

## Contributions

<p>
Contributions are welcome! If you want to improve facial detection, add new features, or fix issues, feel free to submit a pull request. </br>If you encounter any problems or have any suggestions for improvement, you can contact me through my profile on <a href="https://github.com/SidneyTeodoroJr" target="_blank">GitHub</a> or through my social networks listed below.
</p>

<hr>
</br>

<div align="center">
<a href="https://www.facebook.com/profile.php?id=100091086461235" target="_blank"><img src="https://img.shields.io/badge/-Facebook-%230077B5?style=for-the-badge&logo=facebook&logoColor=white" style="border-radius: 30px" target="_blank"></a>
<a href="https://www.instagram.com/sidneyteodoroaraujo" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white"</a>
<a href="https://www.linkedin.com/in/sidney-teodoro-4a4a8119b?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B%2FevuTOiSSJS2hWGCZgtZiQ%3D%3D" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" style="border-radius: 30px" target="_blank"></a>
</div>
