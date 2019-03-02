# SensorDataAnalysis

第一部分
目标
Exploratory analysis of the car_sensor_data dataset.

数据描述
car_sensor_data
This dataset is captured by the numerous sensors installed in an electronic car.

任务
1. For what period is this set of data captured?
2. How many of the features appear to be constant machine settings?
3. Plot the daily mean for 温度检测点1号温度 and 温度检测点2号温度.
1. Are the two trends significantly different?
2. Which days are missing?
3. Fill the missing values with a reasonable method and detrend.
4. What period appears to have an abnormal value compared to a baseline?
Describe any preliminary statistical method that detects temporal anomaly.


第二部分
目标
Machines in a manufacturing line capture real time data in the manufacturing
process through sensors. Factory X has upgraded their machines for that data
collection capability a year ago, and now they have accumulated some data. Many
of the data streams are error messages that alert the handling engineer something’s
wrong upstream. The engineers observed that certain alerts seem to occur together,
perhaps pointing to a specific signature of failure event that the manufacturing
process is experiencing. They’d like to use the data to verify if these patterns exist.

数据描述
alert_id
alert_message : the error message when the alert is raised
message_id : the error message code
event_history
event_id : failure event ID
id : comma-separated list of alerts that occurred for a given failure event

任务
1. Tabulate the top 10 most commonly occurring alerts, with the frequency of
their occurrence.
2. Cluster alerts based on their co-occurrence history. That is, create clusters
of alerts that have the highest probability of occurring together (or one after
another). Each alert can belong to just one cluster.
3. Based on your clustering results, describe the practical recommendation
you’d give to the handling engineer who monitors the occurrences of these
alerts.
