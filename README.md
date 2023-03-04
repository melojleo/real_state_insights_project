# House Rocket - Portifolio price analysis and recommendations

![icon]("https://github.com/melojleo/real_state_insights_project/blob/main/images/house_rocket.png")

House Rocket is a fictional company that aims to analyze property data (real estate) and carry out purchase and sale operations, maximizing profit and taking into account mainly:
- The condition of the property and
- The time of year

The project in question addresses the creation of a complete solution, in the form of an interactive panel hosted in the cloud, for analysis from the point of view of the company's CEO on which are the best deals available on the market. The dashboard includes visualizations, descriptive statistical analysis, business insights, and buy and sell recommendations.

**O dashboard interativo pode ser acessado em: https://huggingface.co/spaces/melojleo/real_state_insights_project**


# 1. Description - Business Issues
Finding the best business opportunities: buying houses in good condition and at low prices, and selling these acquired properties at a higher and fair price. Property attributes, such as location, number of rooms, areas and dates of construction and renovation directly influence their attractiveness and price.


# 2. Dataset and attributes
Originally downloaded from <url>https://www.kaggle.com/harlfoxem/housesalesprediction/discussion/207885</url>. The dataset contains property data in the city of Seattle/USA.

Definitions of relevant attributes:

id - Unique ID for each home sold
date - Date of the home sale
price - Price of each home sold
bedrooms - Number of bedrooms
bathrooms - Number of bathrooms, where .5 accounts for a room with a toilet but no shower
sqft_living - Square footage of the apartments interior living space
sqft_lot - Square footage of the land space
floors - Number of floors
waterfront - A dummy variable for whether the apartment was overlooking the waterfront or not
view - An index from 0 to 4 of how good the view of the property was
condition - An index from 1 to 5 on the condition of the apartment,
grade - An index from 1 to 13, where 1-3 falls short of building construction and design, 7 has an average level of construction and design, and 11-13 have a high quality level of construction and design.
sqft_above - The square footage of the interior housing space that is above ground level
sqft_basement - The square footage of the interior housing space that is below ground level
yr_built - The year the house was initially built
yr_renovated - The year of the house’s last renovation
zipcode - What zipcode area the house is in
lat - Lattitude
long - Longitude
sqft_living15 - The square footage of interior housing living space for the nearest 15 neighbors
sqft_lot15 - The square footage of the land lots of the nearest 15 neighbors




