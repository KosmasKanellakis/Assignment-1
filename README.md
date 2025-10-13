# Assignment-1

This repository contains a Jupyter Notebook for a comprehensive data analysis of Airbnb listings in Athens. The analysis leverages pandas for data manipulation, and matplotlib and folium for data visualization to extract insights from the Athens Airbnb market.

## Prerequisites

Before running the analysis, ensure you have the following installed:
*   Python 3
*   pandas
*   matplotlib
*   folium

You will also need the following dataset files in the same directory as the notebook:
*   `listings.csv`
*   `calendar.csv`
*   `reviews.csv`

## Installation

You can install the required Python libraries using pip:

```bash
pip install pandas matplotlib folium
```

## Running the Analysis

To execute the analysis, run the `Assignment1.ipynb` notebook using a Jupyter environment. The notebook will perform all calculations, generate plots, and save an interactive map as an HTML file.

1.  Clone this repository to your local machine.
2.  Place the required `.csv` dataset files in the root directory of the cloned repository.
3.  Open and run the `Assignment1.ipynb` notebook.


## Analysis and Visualizations Overview

The notebook performs several distinct analyses on the Airbnb data:

### 1. Neighborhood Popularity
Ranks Athens neighborhoods based on the total number of listings, displaying them in descending order of popularity.

### 2. Neighborhood Price Analysis
Creates a detailed table showing the median price, mean price, standard deviation, and a count of listings for each neighborhood, sorted by median price in descending order.

### 3. Daily Availability
Generates a plot that visualizes the number of available listings per day over the period covered by the dataset.

### 4. Reviews and Occupancy
*   Creates a histogram showing the distribution of the number of reviews per listing.
*   Calculates the average occupancy per listing per month, assuming half of all bookings result in a review.
*   Estimates the average monthly income per listing based on a three-night stay per booking and the average price across all listings.

### 5. Room Type Distribution
Displays the number and percentage of listings for each room type (e.g., "Entire home/apt", "Private room") and breaks down these counts by neighborhood.

### 6. Daily Price Trends
*   Calculates the average price per listing per day.
*   Generates a graph visualizing the average price across all listings for each day.

### 7. Listings per Host
Ranks hosts by the number of listings they manage and creates two plots showing the distribution of listings per host: one with a linear scale and one with a logarithmic scale for the host rank.

### 8. Interactive Map of Listings
Generates an interactive map (`map.html`) using Folium, which displays each listing as a point on a map of Athens. Clicking on a listing's marker reveals its description in a popup.
