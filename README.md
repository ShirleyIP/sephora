# Sephora Product Brand and Category Analysis Tool

This project provides a graphical user interface (GUI) for analyzing product brand data and their respective reviews. Using Python libraries like Pandas, Matplotlib, and Tkinter, the tool allows users to explore product brands, categories, and detailed information about popular products.

## Features

- **Total Unique Brands**: Displays the total number of unique product brands.
- **Most Popular Brands**: Lists the top 10 most popular brands based on the number of 'loves' received, along with a bar chart visualization.
- **Unique Categories**: Shows all unique product categories, including primary, secondary, and tertiary categories.
- **Most Popular Categories**: Displays the top product categories and visualizes them in bar charts.
- **Most Popular Product**: Shows details about the most popular product, including an image.
- **Product with Most Reviews**: Displays the product that has the highest number of reviews, along with average ratings.

## Requirements

Make sure you have the following libraries installed:

- Python 3.x
- Pandas
- Matplotlib
- Tkinter (usually comes with Python)
- Pillow (for image handling)

You can install the required libraries using pip:

```bash
pip install pandas matplotlib pillow
```

## Usage

1. **Data Preparation**: Ensure that you have the following CSV files in the same directory as the script:
   - `cleaned_product_info.csv`: Contains cleaned product information.
   - `cleaned_reviews_*.csv`: Contains cleaned review data (multiple files are supported).

2. **Run the Application**: Execute the script in your terminal or command prompt:
   ```bash
   python your_script_name.py
   ```

3. **Explore the GUI**: Use the buttons to navigate through the functionalities:
   - Click on any button to display the corresponding information in the text area.

## Directory Structure

```
your_project_directory/
│
├── cleaned_product_info.csv
├── cleaned_reviews_1.csv
├── cleaned_reviews_2.csv
├── your_script_name.py
└── Sephora.png
```

## Notes

- Ensure that the image paths provided in the script are valid for displaying product images.
- Customize the file pattern in the script if your cleaned reviews follow a different naming convention.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- Special thanks to the contributors who provided the dataset and tools used in this project.
- This project utilizes the following libraries: Pandas, Matplotlib, Pillow, and Tkinter.





# Sephora Product Recommendation System

## Overview

This document provides an overview of the Product Recommendation System implemented in Python using Tkinter for the GUI. The application allows users to receive personalized product recommendations based on various skin and hair attributes.

## Features

- **User Input Options**: Select skin tone, eye color, skin type, hair color, and minimum rating.
- **Dynamic Filtering**: Categories update based on selected skin type.
- **Multiple Brand Selection**: Users can choose multiple brands from a scrollable list.
- **Formatted Output**: Recommendations displayed clearly with product details.

## Requirements

- **Python Version**: 3.x
- **Libraries**:
  - `pandas`
  - `tkinter` (included with Python)

## Installation

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Install Required Packages**:
   ```bash
   pip install pandas
   ```

3. **Prepare Data**:
   - Ensure `cleaned_product_info.csv` and `cleaned_reviews_*.csv` are in the same directory as your script.
   - The dataset should contain the necessary columns for product and review information.

## Usage

1. **Run the Application**:
   ```bash
   python product_recommendation_system.py
   ```

2. **Select Preferences**:
   - Choose skin tone, eye color, skin type, hair color, and rating.

3. **Select Categories and Brands**:
   - Use dropdowns for category selection and a list for brands.

4. **Get Recommendations**:
   - Click "Get Recommendations" to display personalized product suggestions.

## Example Output

Recommendations will include:

- Product ID
- Product Name
- Brand Name
- Loves Count
- Rating
- Reviews
- Price

## Troubleshooting

- Ensure CSV files are correctly formatted and contain required columns.
- Check that all necessary libraries are installed.
- Verify selections if no recommendations are displayed.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
