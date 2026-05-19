# Shopping App Dataset - Data Analysis & Cleaning

A comprehensive data analysis and cleaning project for e-commerce shopping app datasets. This project processes and analyzes product information across multiple categories from shopping platforms.

## 📋 Project Overview

This repository contains scripts and datasets for analyzing product data from an e-commerce shopping platform. The project focuses on:
- Data cleaning and preprocessing
- Dataset consolidation and analysis
- Handling missing values and data quality issues
- Exploratory Data Analysis (EDA)

## 📁 Project Structure

```
celebal_assignment1/
├── codes/
│   └── code.ipynb              # Main Jupyter notebook for data analysis and cleaning
├── 1stweek_dataset/
│   ├── Combined_dataset.csv    # Consolidated dataset from all categories
│   ├── final_cleaned_dataset.csv # Final cleaned and processed dataset
│   └── [category-specific CSV files] # Individual product category datasets
└── README.md                   # This file
```

## 📊 Dataset Details

### Available Categories

The dataset includes products from multiple categories including but not limited to:
- **Clothing**: Dresses, Shirts, T-shirts, Jeans, Kurtas, Sarees, etc.
- **Footwear**: Shoes, Sandals, Boots, Heels, Flats, etc.
- **Accessories**: Watches, Jewelry, Handbags, Scarves, Sunglasses, etc.
- **Home & Living**: Bedsheets, Towels, Curtains, Rugs, Chair Covers, etc.
- **Beauty & Personal Care**: Lipstick, Foundation, Shampoo, Face Wash, etc.
- **Others**: Mobile Accessories, Headphones, Sports Equipment, etc.

### Data Columns

Each dataset contains the following fields:
- `product_id`: Unique product identifier
- `title`: Product name/title
- `product_description`: Detailed product description
- `rating`: Product rating (1-5)
- `ratings_count`: Number of customer ratings
- `initial_price`: Original price
- `discount`: Discount percentage
- `final_price`: Final selling price (after discount)
- `currency`: Currency (INR)
- `images`: Product image URLs
- `seller_name`: Name of the seller
- `sizes`: Available sizes
- `best_offer`: Best promotional offer
- `more_offers`: Additional offers
- `category`: Product category
- Additional metadata fields

## 🛠️ Tools & Libraries

- **Python 3.x**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Data visualization
- **Jupyter Notebook**: Interactive analysis environment

## 🚀 Getting Started

### Prerequisites
- Python 3.7 or higher
- Jupyter Notebook
- Required packages: pandas, numpy, matplotlib

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/celebal_assignment1.git
cd celebal_assignment1
```

2. Install required dependencies:
```bash
pip install pandas numpy matplotlib jupyter
```

3. Open Jupyter Notebook:
```bash
jupyter notebook
```

4. Navigate to `codes/code.ipynb` and run the cells

## 📝 Usage

1. **Load Data**: The notebook loads individual category CSV files from the `1stweek_dataset` directory
2. **Data Exploration**: Explore data structure, shape, and initial statistics
3. **Data Cleaning**: Handle missing values, duplicates, and data inconsistencies
4. **Analysis**: Perform statistical analysis and generate insights
5. **Export**: Cleaned data is exported as `final_cleaned_dataset.csv`

## 📈 Key Features

- ✅ Multi-category product data consolidation
- ✅ Missing value handling and data quality checks
- ✅ Exploratory data analysis (EDA)
- ✅ Data visualization and statistical summaries
- ✅ Processed and cleaned dataset export

## 📊 Sample Analysis

The notebook includes:
- Data shape and structure analysis
- Missing value identification and treatment
- Statistical summaries (mean, median, count, etc.)
- Category-wise distribution analysis
- Price and discount analysis
- Rating distribution and customer feedback analysis

## 📥 Dataset Files

- **Combined_dataset.csv**: Contains all products merged from individual category files
- **final_cleaned_dataset.csv**: Production-ready cleaned dataset with no missing values
- **Individual Category CSVs** (70+): Separate datasets for each product category

## 🔍 Data Quality

- Total Categories: 70+
- Data Points: Multiple product attributes
- Missing Values: Handled through cleaning process
- Duplicates: Removed during consolidation

## 📝 Notes

- Some sensitive information (seller names, addresses) may be partially masked in raw data
- Prices are in INR (Indian Rupees)
- Dates and temporal information may vary across products
- Data represents snapshot from e-commerce platform

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bugs and feature suggestions.

## 📄 License

This project is open source and available under the MIT License.

## ✉️ Contact

For questions or inquiries about this project, please open an issue on GitHub.

---

**Last Updated**: 2026-05-19  
**Project Type**: Data Analysis & Cleaning  
**Status**: Active
