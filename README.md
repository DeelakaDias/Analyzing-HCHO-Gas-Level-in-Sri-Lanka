<h2>Introduction</h2>
<p>This is focuses on the analysis of formaldehyde (HCHO) levels in Sri Lanka, utilizing data collected from the Sentinel-5P satellite. HCHO is a harmful air pollutant associated with various health issues, including respiratory irritation and cancer risks. Understanding the spatial and temporal patterns of HCHO is essential for assessing air quality, identifying emission sources, and monitoring the effectiveness of air quality regulations.
</p>

<h2>Objectives</h2>

The primary objectives of this coursework are:
<ul>
<li>Utilize data engineering skills to analyze HCHO data in Sri Lanka.</li>
<li>Understand the importance of HCHO monitoring for air quality and climate studies.</li>
<li>Develop insights into potential HCHO sources and spatial/temporal trends.</li>
<li>Develop time series prediction algorithms (such as ARIMA models) to forecast future HCHO levels.</li>
</ul>

<h2>Data Description</h2>
<a href="https://drive.google.com/drive/folders/1xzQ5pIEnaUN2DOyZTqYSJrxFMC8Unx73?usp=sharing">Link to dataset</a>
<p>The dataset contains daily HCHO measurements from the Sentinel-5P satellite for seven cities in Sri Lanka: Colombo Proper, Deniyaya (Matara), Nuwara Eliya Proper, Bibile (Monaragala), Kurunegala Proper, Jaffna Proper, and Kandy Proper. The historical data spans from January 1, 2019, to December 31, 2023. Each row of the dataset includes the HCHO reading, location, current date, and next date.
</p>


<h2>Tasks</h2>

<h3>Data Preprocessing</h3>
<ul>
  
<li>Clean and prepare the data by addressing missing values, outliers, and format inconsistencies.
<li>Explore descriptive statistics to summarize HCHO levels for each city and visualize data distribution using histograms, boxplots, or other visualizations.</li>

</ul>

<h3>Spatio-Temporal Analysis</h3>
<ul>
<li>Analyze trends over time, identify seasonal variations, and compare trends across cities, Changes in gas emissions due to the COVID-19 lockdowns</li>
  <br>
      <ul>
          <li><a href="https://github.com/DeelakaDias/Analyzing-HCHO-Gas-Level-in-Sri-Lanka/assets/127048309/5246dacb-ce40-4449-9d60-b03fbc103cdb">Average HCHO Reading by Month for year 2019 - 2023</a>
          </li>
          <br>
          <li><a href="https://github.com/DeelakaDias/Analyzing-HCHO-Gas-Level-in-Sri-Lanka/assets/127048309/d38b9069-6cd9-4a93-a5ad-5abca179ed12">Average HCHO Reading by Year</a>
          </li>
          <br>
          <li><a href="https://github.com/DeelakaDias/Analyzing-HCHO-Gas-Level-in-Sri-Lanka/assets/127048309/a2b469b9-3e09-4e4a-a141-312fa24ddab6">Average HCHO Reading by Year for Each City</a>
          </li>
          <br>
          <li><a href="https://github.com/DeelakaDias/Analyzing-HCHO-Gas-Level-in-Sri-Lanka/assets/127048309/3afa655d-9cff-4ca6-8a40-c61b41e9f0d4">Average HCHO Readings before pandemic</a>
          </li>
          <br>
          <li><a href="https://github.com/DeelakaDias/Analyzing-HCHO-Gas-Level-in-Sri-Lanka/assets/127048309/bb0ec952-13fa-4fbd-8d6f-96d9f07f813e">Average HCHO Readings during pandemic</a>
          </li>
          <br>
          <li><a href="https://github.com/DeelakaDias/Analyzing-HCHO-Gas-Level-in-Sri-Lanka/assets/127048309/d7b38467-a184-4039-a57d-786938990828">Average HCHO Readings after pandemic</a>
          </li>
          <br>
      </ul>
      
<li>Correlate HCHO levels with external factors such as weather, fire events, or anthropogenic activities.</li>
  <li><a href="https://github.com/DeelakaDias/Analyzing-HCHO-Gas-Level-in-Sri-Lanka/assets/127048309/79c8b0b3-1b53-431a-b046-27491c07dabc">Heatmap of Weather and HCHO Readings in Colombo</a>
  </li>
  <br>
  <li><a href="https://github.com/DeelakaDias/Analyzing-HCHO-Gas-Level-in-Sri-Lanka/assets/127048309/0f4fcc84-746c-456d-87a6-a7d788294c77">Heatmap of Weather and HCHO Readings in Kurunegala</a>
  </li>
  <br>
  <li><a href="https://github.com/DeelakaDias/Analyzing-HCHO-Gas-Level-in-Sri-Lanka/assets/127048309/76120a5a-75b7-40e7-8760-a4c5498af4e9">Heatmap of Weather and HCHO Readings in Nuwara Eliya</a>
  </li>
  <br>
</ul>

<h3>Machine Learning</h3>
<ul>
<li>Develop a machine learning model (e.g., ARIMA) to predict future HCHO levels based on historical data.</li>
<li>Evaluate the model's performance using appropriate metrics such as mean squared error and R-squared.</li>
</ul>
<h2>Conclusion</h2>

<p>
The formaldehyde (HCHO) gas levels in seven major Sri Lankan cities—Columbo, Jaffna, Kurunegala, Nuwara Eliya, Monaragala, Matara, and Kandy—were examined in this study. By applying predictive modeling methods and time-series data analysis, we were able to pinpoint temporal trends and spatial variations in HCHO concentrations. Using ARIMA models, we projected future HCHO levels for every city, offering important insights into possible health risks related to the environment. The uncertainty assessment of our findings highlights the significance of using reliable modeling and data collection techniques. Policymakers and other stakeholders involved in public health and urban environmental management initiatives throughout Sri Lanka can benefit greatly from the guidance provided by these findings.
</p>