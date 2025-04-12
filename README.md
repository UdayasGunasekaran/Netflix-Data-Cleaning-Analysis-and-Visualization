# Netflix Data Cleaning, Analysis, and Visualization Using Power BI

## Project Overview
Netflix is a leading streaming platform offering an extensive library of movies, TV shows, and original content. This project focuses on cleaning, analyzing, and visualizing Netflix content data from 2008 to 2021 using Power BI. The objective is to extract meaningful insights into Netflix's content distribution, trends, and audience preferences.

## Dataset Description
The dataset comprises **8790 rows** and **10 columns**, capturing key attributes of Netflix content:

- **show_id** – Unique identifier for each show/movie.
- **type** – Specifies whether the content is a TV show or a movie.
- **title** – Title of the show or movie.
- **director** – Name of the director.
- **country** – Country of origin.
- **date_added** – Date the content was added to Netflix.
- **release_year** – Year of content release.
- **rating** – Age rating or restriction.
- **duration** – Duration of the content (expressed in minutes for movies or seasons for TV shows).
- **listed_in** – Genre classification of the content.

## Data Cleaning Process
Before conducting analysis, the dataset undergoes rigorous cleaning to ensure accuracy and consistency:

1. **Handling Missing Values** – Imputing missing data where possible and removing incomplete entries.
2. **Data Type Conversion** – Transforming necessary fields (e.g., converting `date_added` into DateTime format).
3. **Standardization** – Normalizing categorical values such as genres and country names.
4. **Data Splitting** – Extracting numeric values from the duration column to facilitate analysis of seasons and movie durations.

## Power BI Dashboard Overview
The Power BI dashboard provides an intuitive and visually engaging representation of Netflix’s content catalog. It offers dynamic insights into content trends and audience preferences.

### Dashboard Features
The dashboard includes the following key metrics and visuals:

- **Total Content** – Displays the aggregate count of all movies and TV shows available on Netflix.
- **Year Data** – Tracks the distribution of content by release year, illustrating Netflix’s growth trends.
- **Total Genres** – Highlights the total count and diversity of genres.
- **Total Minutes & Total Hours** – Represents the combined duration of all content in minutes and hours.
- **Total Seasons** – Summarizes the total number of seasons across all TV shows.
- **Content Type Distribution** – Categorizes content into Movies and TV Shows for simplified analysis.
- **Country Breakdown** – Identifies the countries associated with Netflix content, showcasing geographic diversity.
- **Top 10 Ratings** – Displays the highest-rated content, offering insights into audience preferences.
- **Monthly Releases** – Illustrates the monthly pattern of new content added to Netflix.
- **Yearly Releases** – Highlights annual trends in Netflix's content additions.
- **Top 10 Genres** – Provides insights into the most frequently occurring genres.
- **Content Distribution** – Presents a breakdown of Movies vs. TV Shows.
- **Top 10 Directors** – Recognizes directors with the most contributions to Netflix’s catalog.

![image](https://github.com/user-attachments/assets/c6612cc0-9d61-40a5-9245-1cf0ac30b2dd)


## Key Measures and Calculated Columns
The dashboard leverages calculated metrics to refine insights:

- **GenreCount** – Computes the frequency of each genre in the dataset.
- **Duration_Seasons** – Extracts the number of seasons for TV shows.
- **Duration_Minutes** – Splits the total duration of movies into minutes.

## Purpose & Business Insights
This Power BI dashboard serves as a **dynamic analytical tool** for identifying trends, patterns, and key performance metrics in Netflix’s content offerings. It is designed for data enthusiasts, professionals, and researchers interested in exploring content distribution and audience engagement.

## How to Use This Project
1. **Load the Dataset** – Import the cleaned dataset into Power BI.
2. **Perform Data Cleaning** – Use Power Query to apply necessary transformations.
3. **Develop Visualizations** – Create compelling insights using DAX measures and calculated columns.
4. **Analyze and Share Findings** – Use the dashboard to interpret content trends and derive valuable insights.

---

### Notes:
- Ensure dataset integrity before conducting analysis.
- Customize visualizations based on business or research requirements.
- Explore advanced filtering techniques to refine insights.

