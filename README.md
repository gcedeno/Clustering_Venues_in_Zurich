# Description
> This Repository contains all the files corresponding to the capstone project of the IBM Data Science Professional Certificate. This submission includes the Jupyter Notebook, Final Report(pdf File) and Presentation(slides.HTML) for the whole project. All the required tasks to accomplish the project goals are part of this final report.

### Problem or idea Definition
> The main goal of this project is to provide business intelligence for an international company that is willing to open a new restaurant supply shop in Zürich. The target market for this kind of business is limited to those within the culinary community. This includes: restaurants, culinary schools, cafeterias(including medical and schools), bars, caterers, bakeries and coffee shops. Therefore, it is of major importance clustering places around the city and find out which ones of those concentrate venues which belong to the target market. This information will help decision makers choosing the right place for opening shops, planning logistics, calculating costs and designing better marketing campaigns.

### Data Source
> The whole data for this project is gathered from the web and from Foursquare location data service using their API. The idea is to create a dataset containing the different neighborhoods in the city of Zürich according to their respective postal codes, then add the geographical coordinates and venues information and location in each neighborhood. The final resulting dataset is used for creating clusters with different venues and find out which clusters constitute important segments to direct marketing campaigns.
>1. **Zurich - postal codes**
>All the information regarding postal codes for the different neighborhoods in the city of Zürich will be gathered from the website [geonames_postalcodes_CH](https://www.geonames.org/postal-codes/CH/ZH/zurich.html) performing web scraping with the help of BeatifulSoup and then converting the data into a pandas DataFrame for further analysis.
>2. **Additional Data via the Foursquare API**
> All the data related to venues will be gathered from Foursquare location data using their API. [Foursquare](https://foursquare.com/)
### Presentation
From the terminal or command line, use the following expression:
jupyter nbconvert Capstone_Project_Presentation.ipynb --to slides --post serve --template output-toggle
This should open a tab in your web browser where you can scroll through the presentation. Sub-slides can be accessed by pressing 'down' when viewing its parent slide.
