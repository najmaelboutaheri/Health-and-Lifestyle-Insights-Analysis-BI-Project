<img width="542" alt="image" src="https://github.com/user-attachments/assets/dab3eba8-3725-429c-88d8-d0e036fb769f" /># Health and Lifestyle Insights Analysis

## Overview
This project focuses on analyzing survey data related to health and lifestyle habits. Using tools like Power BI and Python, we explore trends in sleep quality, diet, exercise, and overall energy levels across different demographics.

The analysis aims to uncover actionable insights that can help improve well-being and foster healthy habits.

---

## Table of Contents
- [Dataset Description](#dataset-description)
- [Methodology](#methodology)
- [Key Findings](#key-findings)
- [Technologies Use](#Tools-Used)
- [How to Run](#how-to-run)
- [Contributing](#contributing)
- [License](#license)

---

## Dataset Description
The dataset contains survey responses from 152 participants, categorized by:
- **Demographics**: Age, gender, city, and occupation.
- **Health Metrics**: Sleep quality, energy levels, diet type, and exercise frequency.
- **Behavioral Patterns**: Healthy and Fast Food  consumption, exercise duration, and sleep hours.

Data was collected using **Google Forms**, and the responses were uploaded to **Google Sheets**. The dataset was integrated into Power BI using the **Direct Query mode** for real-time analysis.

## Methodology
1. **Data Collection**: Conducted surveys via Google Forms.
2. **Real-Time Integration**: Connected Google Sheets to Power BI using Direct Query mode for real-time updates.
3. **Data Cleaning**: Ensured accurate and consistent data by handling missing and inconsistent entries.
4. **Data combination**: Combine all the forms sheets by adding an other column 'City' that indicates the location of each Respondents.
5. **Data modeling**: Use Star schema with the creation of fact table and dimension tables to simplify analysis.
   
  <img width="542" alt="image" src="https://github.com/user-attachments/assets/3dbb8d95-f4f4-47aa-9045-5e4bcc2da241" />

6. **Power BI Dashboards**: Developed interactive dashboards for in-depth insights.
   
## Reports pages:
The project was devided into 4 pages:
- An overview
  
  <img width="575" alt="image" src="https://github.com/user-attachments/assets/5a4319a3-1fac-4f2f-b488-3e23e56c000b" />

- Exercise Habits analysis
  
  <img width="574" alt="image" src="https://github.com/user-attachments/assets/4b989040-c1d9-4db1-a051-f9732bb9dd15" />

- Sleep analysis
  
  <img width="575" alt="image" src="https://github.com/user-attachments/assets/78d70f1c-8794-4307-9f6c-058a8e76ed73" />

- Diet Analysis
  
  <img width="578" alt="image" src="https://github.com/user-attachments/assets/657fff17-3622-4bbd-9968-1beb8bfc4866" />

- Health and Mood Analysis
  
  <img width="577" alt="image" src="https://github.com/user-attachments/assets/e268f362-2978-45bf-b1c5-58664a3b2d40" />
  
## Key Findings
### 1. **Demographics**
   - Most respondents were aged 18-25 and primarily students.
   - Hoceima was the most represented city.
   - The data was collected from people located in these 4 cities: Al Hoceima, Tangier, Rabat and Tetouane.

### 2. **Health Insights**
   - **Sleep Quality**:
      --->57.89% of respondents reported "Somewhat restful" sleep.
      --->Engineers exhibited higher instances of "Not restful" sleep.
   - **Energy Levels**:
      --->Moderate energy levels were most common (53%).
      --->Higher energy levels correlated with consistent exercise patterns.

### 3. **Exercise Habits**
   - Cardio was the most popular exercise type (27%).
   - Participants exercising 2-3 days per week reported better mood levels.

### 4. **Diet Patterns**
   - A balanced diet was most prevalent, followed by high-protein diets.
   - Frequent fast-food consumers showed lower energy levels and poorer sleep quality.

## Tools Used
- **Google Forms**: For data collection.
- **Google Sheets**: For storing and managing survey responses.
- **Power BI**: For creating interactive dashboards and real-time visualizations using Direct Query mode.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/health-lifestyle-analysis.git
   ```
2. Install power bi desktop from: [Power Bi Desktop](#https://r.search.yahoo.com/_ylt=AwrkELXt1W5n8gEAnZAk24lQ;_ylu=Y29sbwNpcjIEcG9zAzEEdnRpZAMEc2VjA3Ny/RV=2/RE=1736526573/RO=10/RU=https%3a%2f%2fwww.microsoft.com%2ffr-fr%2fdownload%2fdetails.aspx%3fid%3d58494/RK=2/RS=7J4VnoGx_Sb501Y.VgXIkAqJxCs-)

3. Open the Power BI report ```'Health_Lifestyle_Analysis.pbix'``` for interactive exploration. Ensure the linked Google Sheet is active for real-time updates.
## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## Fundings and Insights

**Demographics**:
   - The majority of respondents (44.7%) were aged 18-25, with most identifying as students.
   - Hoceima had the highest number of respondents compared to other cities.

**Sleep Quality**:
   - 57.89% of participants described their sleep as "Somewhat restful."
   - Engineers reported the highest percentage of "Not restful" sleep compared to other occupations.

**Energy Levels**:
   - Moderate energy levels were the most common across respondents, especially among those exercising 2-3 days per week.
   - High energy levels were correlated with participants who followed a balanced diet and engaged in regular exercise.

**Exercise Habits**:
   - Cardio (e.g., running, cycling) was the most frequent exercise type (26.97% of participants).
   - Most respondents exercised 2-3 days per week, with these participants showing better mood levels and energy trends.

**Diet Patterns**:
   - A balanced diet was the most reported dietary preference, followed by high-protein diets.
   - Those consuming fast food frequently had lower energy levels and poorer sleep quality.

**Behavioral Trends**:
   - Respondents exercising for 30-60 minutes daily showed higher energy levels.
   - Participants consuming fruits and vegetables regularly reported better overall health feedback.

These insights suggest strong links between lifestyle choices (diet, exercise, and sleep) and overall well-being, providing valuable directions for health improvement strategies.
Explore more insights in the Power BI dashboard!

## License
This project is licensed under the MIT License. See the LICENSE file for details.
