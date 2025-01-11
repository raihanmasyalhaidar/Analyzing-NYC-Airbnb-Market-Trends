<div align="center">

# Analyzing-NYC-Airbnb-Market-Trends

</div>

<div align="justify">

![image](https://github.com/user-attachments/assets/85c7b169-a759-4668-9849-d64d922a2ac8)


## Overview
Airbnb is one of the leading platforms in the sharing economy, enabling property owners to rent out their spaces to travelers worldwide. With its rapid growth across cities and countries, Airbnb has transformed the travel industry by offering a flexible alternative to traditional accommodations such as hotels.

In this project, we will take a closer look at the New York Airbnb market from 2019. This project uses RStudio as the main tool for coding, visualization, and documentation. The analysis focuses on providing insights based on the data for customers and property developers.

## Objectives
1. Identify price patterns based on listing locations
2. Analyze room types most preferred by travelers
3. Assess the relationship between recent guest reviews and listing availability
4. Provide strategic recommendations to improve market performance

## Dataset
The data used is sourced from :

<div align="center">
  
https://www.kaggle.com/datasets/raniajaberi/airbnb-price/data

</div>

### Data Structure

**data/airbnb_price.csv**
This is a CSV file containing data on Airbnb listing prices and locations.
- **`listing_id`**: unique identifier of listing
- **`price`**: nightly listing price in USD
- **`nbhood_full`**: name of borough and neighborhood where listing is located

**data/airbnb_room_type.xlsx**
This is an Excel file containing data on Airbnb listing descriptions and room types.
- **`listing_id`**: unique identifier of listing
- **`description`**: listing description
- **`room_type`**: Airbnb has three types of rooms: shared rooms, private rooms, and entire homes/apartments

**data/airbnb_last_review.tsv**
This is a TSV file containing data on Airbnb host names and review dates.
- **`listing_id`**: unique identifier of listing
- **`host_name`**: name of listing host
- **`last_review`**: date when the listing was last reviewed

## Methodology
1. **Data Cleaning**:
   * Cleaning the data by removing duplicates, handling missing values, and converting data types
2. **Exploratory Data Analysis (EDA)**:
   * Using visualizations to understand price distributions, room type preferences, and review trends
3. **Modeling**:
   * Building simple statistical models to analyze relationships between variables
4. **Summary & Recommendations**:
   * Compiling a final report based on the analysis results


## Summary
Based on the data, the majority of Airbnb listings offer entire home/apt and private room, with an average price of $141.78, reflecting a balance between comfort and affordability. Private room (11,356 units) provides more privacy at a lower price ($81.64) compared to entire home/apt, which is more expensive ($197.17). Shared room is the cheapest option with an average price of $53.47, but it is less popular due to limited privacy. While most of the highest-priced listings are entire home/apt, there is also a private room listed for $7500, indicating that factors such as location and exclusive amenities can influence price. The majority of listings fall within the $50-$199 price range, making it affordable for many guests, while listings under $50 or above $200 are less common. Finally, Michael and Sonder (NYC) are the hosts with the most reviews, reflecting high guest satisfaction. Overall, Airbnb offers a variety of accommodations catering to different budgets, with a flexible balance between comfort, privacy, and price.

## Recommendations
1. **Increase Private Room Listings:** Since private rooms are popular and moderately priced, hosts should consider offering more options in this segment to balance privacy and affordability
2. **Focus on Mid-Range Listings:** Encourage more listings within the $50-$199 price range to cater to budget-conscious travelers while maintaining comfort
3. **Diversify Premium Listings:** Expand luxury or unique entire home/apartment listings to justify higher prices, while keeping affordable options available
4. **Improve Shared Room Options:** Enhance shared rooms by ensuring better privacy and amenities, making them more attractive to budget travelers.
5. **Encourage Positive Guest Experiences:** Hosts with high review counts, like Michael and Sonder (NYC), should be a model for excellent guest interactions, quality, and consistency
6. **Tailor Listings to Locations:** Adjust listings based on location-specific demand, offering premium options in high-demand areas and budget-friendly options elsewhere
7. By implementing these strategies, Airbnb can better serve various customer segments while maintaining a balance between affordability and comfort
