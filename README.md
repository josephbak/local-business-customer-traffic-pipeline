# Local Business Popularity and Customer Traffic Analysis Pipeline

This project analyzes the popularity of local businesses in a specified area by extracting data from the **Google Places API** and **Yelp Fusion API**. It integrates this data to visualize high-traffic locations and provide insights into business popularity based on ratings and customer feedback.

## Project Overview

- **Goal**: Identify high-traffic and popular business locations to support competitive analysis and market research.
- **APIs Used**:
  - **Google Places API**: For business details, ratings, and location data.
  - **Yelp Fusion API**: For additional business ratings, review counts, and categories.
- **Pipeline Steps**:
  - Extract data from Google Places and Yelp APIs.
  - Transform and merge data to calculate popularity scores.
  - Visualize business locations on a map with popularity indicators.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [How to Run](#how-to-run)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## Technologies Used

- **Python**: For data extraction, transformation, and analysis.
- **Google Places API** and **Yelp Fusion API**: To obtain business data for analysis.
- **Pandas**: For data manipulation and transformation.
- **Plotly/Folium**: For interactive, map-based visualizations.
- **SQLite**: Local database to store processed data.

---

## Setup and Installation

### Prerequisites

- Python 3.x
- Google Cloud and Yelp Developer accounts (for API access)
- Basic knowledge of working with APIs and data manipulation in Python

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/local-business-popularity.git
   cd local-business-popularity