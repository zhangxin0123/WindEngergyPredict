#WindEngergyPredict
#Group Project of using machine learning predicting wind energy in ireland with data from 'Ireland Weather' and 'Installed Wind Capacity-Ireland'
#Purpose&Business Implication: The machine learning quest for grid inertia is an example of the matter adjustments required to accommodate the move in energy production and use that is now going on. The variable nature of the wind cannot be eliminated but predicted. The early results in this paper suggest that we can use the machine learning algorithm to make wind power sufficiently more predictable and valuable. Furthermore, this approach can also benefit the digitalization of wind farm operations with greater data rigour. As machine learning can help wind operators work smarter, swifter and more data-driven assessments of how the power output better meets electricity demand. In addition, developing green power requires more than just installing wind turbines and expanding storage. It is vital to make the electricity grids cope intelligently. Smart grid applications like adaptive charging of EV vehicles, charging of batteries by industrial users (data centres) or automated launching of washing machines when there is excess energy are examples of how an intelligent electricity grid can complement the increased amount of renewable energy production. Many companies are attempting to switch from being makers into fully digital businesses. Machine learning application in renewable energy has been deployed positively. General Electric, the U.S. industrial giant for power generation, uses A.I./ Machine Learning designed digital twin of the wind turbine logistics process to accurately predict and streamline logistics costs, enabling a 10% reduction in logistics costs (Alhart, 2022). We hope that the machine learning approach can strengthen the business case for wind power, drive further adoption of carbon-free energy on electric grids, and develop innovative ideas for how society can make the best of variable power sources like wind energy.
# Finding data: 
For our analysis we use hourly historical weather data per weather station as provided by Met Éireann under a Creative Commons Attribution 4.0 International (CC BY 4.0) license (Met Éireann, n.d.). The datasets contain 16 features like date, rainfall, temperature, wet bulb air temperature, dew point air temperature, vapour pressure, relative humidity, mean sea level pressure, wind speed, wind direction, and several indicators. Since the datasets were too large to be handled on our P.C.s, and we only needed the time range from 2015 to 2022, we deleted the data before 2015 manually, leaving us with 62112 rows of data per weather station. Additionally, we decided to use only five weather stations since they are sufficient to create an average of the Irish national weather.The wind energy data is retrieved from entsoe, a central collection of electricity generation, transportation and consumption data for the pan-European market. It depicts the amount of produced wind-energy in Ireland (whole Island) on an hourly 6 basis and spans from 2015 to 2022. Since this is the shorter period of time, we end up with a total of 62,113 rows of data between January 2015 to December 2021.Next, we followed the two steps recommended by (Geron, 2019) which need to be completed before applying any machine learning models to the datasets.
# Exploratory Data Analysis: 
Most of the weather indicators, such as wet bulb temperature, sunshine duration, rain, visibility, or cloud cover do not have a direct influence on wind energy output. The following shows the physical formula for wind energy: 𝐸𝑤 = 12 × 𝐴 × 𝜌 × 𝑣3 × 𝑡 
Where: 
𝐸𝑤 [J] = Wind Energy 
A [m²] = Air flow area
𝜌 [kg/m³] = Air density 
v [m/s] = Wind speed 7 t [s] = time
# Data Preparation (Pre-processing and Cleaning)
# Balancing of Datasets
# Models Employed: 
we has reinvestigated the data of Historical Weather and Energy Production with proposed multiple algorithm models, Which are Random Forest, Lasso Regression, Neural Network, LSTM, ARIMA. The result indicated that the LSTM model has the most satisfactory performance and is likely to be useful in time series prediction in the future intelligent renewable energy grid operation.
details please see paper attached. 
