# Analysis of Deaths Involving Police in the United States

This repository contains a comprehensive analysis of police-related deaths in the United States, based on various datasets. The analysis explores trends, demographics, and geographical patterns related to police killings. Key aspects include examining the racial makeup of individuals involved, the manner of death, mental health-related deaths, and more.

## Dataset

The data used for analysis includes information on police killings across various cities and states in the United States. Each entry provides details such as:
- Age
- Gender
- Race
- Whether the individual was armed
- Location of the incident
- Date of the incident

## Analysis

The following analyses were performed in this repository:

1. **Police Killings Over Time**:
   - A time series analysis showing trends in the number of police killings over the years.
   - Examined if there was a noticeable increase or decrease in the number of killings.

2. **Race and Police Killings**:
   - A breakdown of the racial distribution of individuals killed by police.
   - A separate analysis comparing the racial distribution of police killings in the most dangerous cities.

3. **Mental Illness and Police Killings**:
   - Identified the percentage of individuals killed by police who had been diagnosed with mental illness.

4. **Armed vs Unarmed**:
   - Investigated the percentage of individuals who were armed or unarmed during police killings.
   - Identified the types of weapons (if any) carried by the individuals.

5. **Geographical Analysis**:
   - Visualized the number of police killings by state and by city.
   - Created a choropleth map to show the number of killings by state.
   - Ranked the cities with the highest number of police killings.

6. **Age Analysis**:
   - Investigated the age distribution of individuals killed by police.
   - Calculated the percentage of individuals under 25 years old.

7. **Gender and Manner of Death**:
   - Analyzed whether there was a difference in the manner of death between men and women.

## Tools and Libraries Used

- **Python**: The primary programming language used for analysis.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib / Seaborn**: Visualization of trends, distributions, and patterns.
- **Scikit-learn**: Linear regression for trend analysis.
- **Geopandas**: For creating geographical visualizations like choropleth maps.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Prathamesh326/Analyse-Deaths-involving-Police-in-the-United-States.git
   cd Analyse-Deaths-involving-Police-in-the-United-States
   ```

2. Run the Jupyter notebooks or Python scripts to begin analysis.

## Notebooks

- **police_killings_over_time.ipynb**: Analyze trends over time.
- **race_analysis.ipynb**: Breakdown of police killings by race.
- **mental_illness_analysis.ipynb**: Analyzing mental illness-related deaths.
- **geographical_analysis.ipynb**: Geospatial analysis of police killings.
- **age_gender_analysis.ipynb**: Age and gender-based analysis.

## Contributing

If you would like to contribute to this project, please fork the repository, make your changes, and submit a pull request. Any suggestions for additional analyses or improvements are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
