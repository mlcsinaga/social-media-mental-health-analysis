# Python Scripts

This folder contains all Python scripts used for data analysis in the Social Media Usage & Mental Health Analysis project.

## Files to Upload

Please upload the following Python script files to this folder:

1. **script_1.py** - Data cleaning and preprocessing
2. **script_2.py** - Statistical analysis and business insights
3. **script_3.py** - Visualization generation
4. **chart_script.py** - Anxiety demographics chart generation
5. **chart_script_2.py** - Risk distribution chart generation

## Script Descriptions

### 1. script_1.py - Data Cleaning
**Purpose**: Clean and preprocess raw data
- Load raw dataset
- Handle missing values
- Create derived variables (age groups, screen time categories)
- Export cleaned data

### 2. script_2.py - Statistical Analysis
**Purpose**: Perform comprehensive statistical analysis
- **T-tests**: Screen time differences by anxiety status
- **Chi-square tests**: Association between screen time and mental health
- **Correlation analysis**: Relationships between variables
- **Segmentation**: Create risk profiles (Low/Medium/High)
- **Business metrics**: Calculate KPIs and ROI

**Key Outputs**:
- analyst_executive_summary.csv
- analyst_risk_segmentation.csv
- analyst_demographic_breakdown.csv
- analyst_screen_time_impact.csv

### 3. script_3.py - Visualizations
**Purpose**: Generate data visualizations
- Risk distribution charts
- Mental health vs screen time plots
- Demographic comparison charts
- Export as PNG/JPG for reports

### 4. chart_script.py - Demographics Chart
**Purpose**: Create anxiety rates demographics visualization
- Horizontal bar chart
- Plotly for interactive features
- Export as PNG and SVG

### 5. chart_script_2.py - Risk Distribution Chart
**Purpose**: Create user population distribution by risk level
- Stacked bar chart
- Color-coded risk segments
- Plotly for professional appearance

## Technologies Used

- **Python 3.x**
- **Pandas**: Data manipulation
- **NumPy**: Numerical operations
- **SciPy**: Statistical testing
- **Matplotlib**: Static visualizations
- **Seaborn**: Statistical data visualization
- **Plotly**: Interactive charts

## Requirements

```python
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
scipy>=1.7.0
plotly>=5.0.0
```

## Usage

```bash
# 1. Data cleaning
python script_1.py

# 2. Statistical analysis
python script_2.py

# 3. Generate visualizations
python script_3.py
python chart_script.py
python chart_script_2.py
```

## Key Findings Generated

- **Screen time correlation**: 0.69 hour difference (p < 0.0001)
- **Risk amplification**: 2.6x higher anxiety in high screen-time users
- **Sentiment impact**: 37.4% vs 14.2% anxiety rates
- **Late-night posting**: 25.1% vs 23.6% anxiety rates

---

**Note**: Python script files are not included in this repository. Please contact the project author for access to the code.
