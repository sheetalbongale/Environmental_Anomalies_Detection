# Environmental Anomaly Detection

## Objective
Build, train, optimize, and deploy a machine learning model to a virtual edge device that accurately detects environmental anomalies.

## AWS’s Seattle Spheres
The spheres range from three to four stories tall, house 40,000 plants as well as meeting space and retail stores. The domes are kept at a temperature of 72 °F (22 °C) and 60 percent humidity during the daytime with sensors that collect data about temperature, humidity, light, CO2, dew point, and other environmental variables. They were created to not only provide a creative workspace for AWS employees but to be an example of how to think big about reintroducing nature into urban environments.

## Sample Training Data
Each of the 23 sensors is sampled at 15 minute intervals, therefore a day has 96 values per sensor concatenated with its sensor peers in the following order:

sensorList = ( ‘co2_1′,’co2_2’, ‘co2_3’, ‘co2_4’,
‘temp_1’, ‘temp_2’, ‘temp_3’, ‘temp_4’,
‘dew_1′,’dew_2’, ‘dew_3’, ‘dew_4’,
‘instLight_1’, ‘instLight_2’, ‘instLight_3’,
‘relH_1’, ‘relH_2’, ‘relH_3’, ‘relH_4’,
‘externTemp_1’,
‘externSunrise_1’,
‘externHumid_1’,
‘externCondition_1’,
) + day and hour index


