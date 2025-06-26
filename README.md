# 🚔 Los Angeles Crime Data Analysis (2020-Present)

A comprehensive data analysis project examining crime patterns, trends, and geographic distributions in Los Angeles using Python and advanced statistical techniques.

## 📊 Project Overview

This project analyzes over 1 million crime records from the Los Angeles Police Department (LAPD) spanning from 2020 to present. The analysis provides insights into:

- **Temporal Crime Patterns**: Trends by year, month, day of week, and hour
- **Geographic Hotspots**: Crime distribution across LA police areas
- **Crime Type Analysis**: Frequency and patterns of different crime categories
- **Victim Demographics**: Age and gender distribution analysis
- **Data Quality Assessment**: Comprehensive missing data handling

## 🔍 Key Findings

- **1,000,000+** crime records analyzed after data cleaning
- **Peak Crime Hours**: 12:00 PM and 6:00 PM show highest activity
- **Geographic Patterns**: Central and Hollywood areas show highest crime rates
- **Temporal Trends**: Detailed seasonal and weekly patterns identified
- **Data Retention**: 95%+ of original data retained after quality filtering

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment

## 📁 Project Structure

```
crime/
├── app.ipynb                              # Main analysis notebook
├── Crime_Data_from_2020_to_Present (1).csv   # Dataset (not included in repo)
├── README.md                              # Project documentation
└── requirements.txt                       # Python dependencies
```

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/la-crime-analysis.git
   cd la-crime-analysis/crime
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the dataset**
   - Visit [Los Angeles Open Data](https://data.lacity.org/)
   - Download "Crime Data from 2020 to Present"
   - Place the CSV file in the project directory

4. **Run the analysis**
   ```bash
   jupyter notebook app.ipynb
   ```

## 📈 Analysis Workflow

### 1. Data Loading & Overview
- Dataset information and structure analysis
- Initial data quality assessment

### 2. Data Quality Assessment
- Missing value analysis and reporting
- Data completeness evaluation
- Quality score calculation

### 3. Data Cleaning
- Removal of high-missing columns (>50% missing)
- Invalid data filtering (negative ages, missing coordinates)
- Data type optimization

### 4. Exploratory Data Analysis
- Crime distribution by police areas
- Victim demographics analysis
- Crime type frequency analysis
- Status distribution examination

### 5. Advanced Pattern Analysis
- Temporal feature engineering
- Time-series crime trends
- Seasonal pattern identification
- Peak activity analysis

### 6. Geographic Analysis
- Spatial crime distribution
- Area-wise crime intensity
- Location premise analysis
- Safety scoring system

### 7. Statistical Summary
- Correlation analysis
- Key performance indicators
- Actionable recommendations
- Executive summary

## 📊 Key Visualizations

- **Multi-panel Crime Overview**: 6-subplot comprehensive analysis
- **Temporal Patterns**: Year/month/day/hour trend analysis
- **Geographic Scatter Plot**: Crime location mapping
- **Correlation Heatmap**: Statistical relationships
- **Crime Frequency Categories**: High vs low frequency analysis

## 🎯 Business Intelligence

### Actionable Insights
- **Resource Allocation**: Data-driven patrol deployment
- **Prevention Programs**: Targeted intervention strategies
- **Community Policing**: Area-specific engagement plans
- **Policy Development**: Evidence-based crime prevention

### Performance Metrics
- Daily crime averages
- Peak activity identification
- Geographic risk assessment
- Trend analysis and forecasting

## 🔮 Future Enhancements

- [ ] **Machine Learning Models**: Crime prediction algorithms
- [ ] **Interactive Dashboard**: Real-time crime monitoring
- [ ] **Geospatial Analysis**: Advanced mapping and heat maps
- [ ] **External Data Integration**: Weather, demographics, economics
- [ ] **API Development**: Real-time data ingestion
- [ ] **Mobile Application**: Public safety alerts

## 📝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📊 Data Source

**Dataset**: Crime Data from 2020 to Present  
**Source**: Los Angeles Police Department (LAPD)  
**Portal**: [Los Angeles Open Data](https://data.lacity.org/)  
**Update Frequency**: Weekly  
**License**: Public Domain

## ⚖️ License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Acknowledgments

- Los Angeles Police Department for providing open crime data
- Los Angeles Open Data initiative
- Python data science community

## 📧 Contact

**Project Maintainer**: [Your Name]  
**Email**: [your.email@example.com]  
**LinkedIn**: [Your LinkedIn Profile]  
**Portfolio**: [Your Portfolio Website]

---

**⭐ If you found this project helpful, please give it a star!** 