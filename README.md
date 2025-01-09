# NFL Player Analysis Project

This project analyzes a dataset of NFL players, focusing on player positions, their colleges, and various attributes such as weight, height, and age. The goal is to gain insights into the relationships between these variables, visualize trends, and draw conclusions that could be helpful for understanding the NFL player pool.

## Project Overview

In this project, we use Python to:
- Clean and preprocess data
- Analyze player statistics by position and college
- Visualize the relationships between age, weight, and position
- Explore the number of players from each college and the number of quarterbacks by college

## Data

The dataset includes various attributes of NFL players, including:
- `nflId`: Unique ID for each player
- `height`: Height of the player (in feet and inches)
- `weight`: Weight of the player (in pounds)
- `birthDate`: Birthdate of the player
- `collegeName`: College the player attended
- `position`: Position of the player (e.g., Quarterback, Running Back, etc.)
- `displayName`: Display name of the player

## Steps Taken

### 1. Data Cleaning:
- Removed any rows with missing values in critical columns such as `collegeName`, `age`, and `weight`.
- Converted the height from feet/inches format to centimeters.
- Standardized the birthdate format to ensure consistency.

### 2. Data Analysis:
- **Position-based Analysis**: Analyzed quarterbacks (QB), wide receivers (WR), tight ends (TE), and kickers (K) by examining their weight and age.
- **College-based Analysis**: Counted the number of players from each college, focusing on the top 10 colleges producing the most players and quarterbacks.

### 3. Data Visualization:
- **Density Plots**: Plotted the distribution of weight and age for QBs, WRs, TEs, and Ks, showing concentration and trends in the dataset.
- **Bar Charts**: Created bar charts to display the number of players and quarterbacks from each college. We used horizontal bar charts with reversed color palettes to make the most populated colleges clearer.

## Visualizations

### QB Age vs. Weight (Density Plot)
A density plot visualizing the relationship between the age and weight of quarterbacks.

### WR Age vs. Weight (Density Plot)
A similar density plot for wide receivers.

### TE Age vs. Weight (Density Plot)
A density plot for tight ends.

### K Age vs. Weight (Density Plot)
A density plot for kickers.

### Top 10 Colleges Producing the Most Quarterbacks
A bar chart showing the top 10 colleges with the highest number of quarterbacks.

### Top 10 Colleges Producing the Most Players
A bar chart showing the top 10 colleges with the highest number of players across all positions.

## Installation

### Prerequisites:
To run the code in this project, you need to have Python 3.6+ installed along with the necessary libraries.

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/NFL-Player-Analysis.git
   cd NFL-Player-Analysis

