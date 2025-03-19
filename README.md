# AIR_QUALITY-PREDICTION
Prediction of Air Quality using Historical Data using  UCI datasets.

Air Quality Prediction using Machine Learning
Air pollution has become a significant environmental concern, affecting both public health and climate conditions. This project aims to predict Relative Humidity (RH) using historical air quality data from the Air Quality UCI dataset. By leveraging Facebook Prophet, a powerful time-series forecasting model, we analyze past trends and forecast future values. The dataset includes various environmental factors such as temperature, PM2.5, PM10, NO₂, SO₂, CO levels, population density, and proximity to industrial areas, all of which influence air quality.

To ensure accurate predictions, we performed extensive data preprocessing, including handling missing values, formatting timestamps, and normalizing data. The dataset contained missing values represented as -200, which were replaced with the mean of the respective columns. Date and time columns were combined and converted into a datetime format to align with Prophet’s requirements. Once the data was cleaned, we trained the Prophet model, which effectively captures seasonality, trends, and fluctuations in air quality data.

The model was evaluated using visualization techniques to understand long-term trends and seasonal patterns. The results demonstrated that Prophet successfully predicted future RH values with reasonable accuracy. The visualized forecasts include predicted values along with uncertainty intervals, helping stakeholders understand air pollution trends. This information can be valuable for policymakers, environmental researchers, and city planners in devising strategies to improve air quality.

In the future, this project can be enhanced by incorporating real-time sensor data to make continuous predictions. Additionally, implementing advanced deep learning models such as LSTMs (Long Short-Term Memory) can further improve forecast accuracy. Deploying the model as a web-based application will allow the public and governmental agencies to access real-time air quality predictions and receive alerts when pollution levels exceed safety thresholds.

This project provides a solid foundation for data-driven air quality monitoring and forecasting, offering a practical approach to mitigating the harmful effects of air pollution. Contributions and improvements are welcome to enhance the accuracy and usability of this model. 
