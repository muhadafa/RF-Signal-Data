# RF-Signal-Data
RF Signal data acquired via SDR H/W interfaced to DragonOS Focal.

https://www.kaggle.com/datasets/suraj520/rf-signal-data
About Dataset
The generated dataset contains radio frequency (RF) signal data for a period of one month, from May 5, 2023, to June 11, 2023 collected via SDR hardware interfaced to DragonOS Focal. Each row of the dataset represents a single RF signal observation, with various features that describe the signal and its environment.

The dataset can be used for tasks such as machine learning, statistical analysis, and signal processing.

The following is a detailed description of each feature in the dataset:
Timestamp: The date and time of the signal observation.
Frequency: The frequency of the RF signal in Hertz (Hz).
Signal Strength: The strength of the RF signal in decibels relative to one milliwatt (dBm).
Modulation: The modulation type used for the RF signal. Possible options include Amplitude Modulation (AM), - ---
Frequency Modulation (FM), Quadrature Amplitude Modulation (QAM), Binary Phase Shift Keying (BPSK), Quadrature - Phase Shift Keying (QPSK), and 8 Phase Shift Keying (8PSK).
Bandwidth: The bandwidth of the RF signal in Hertz (Hz).
Location: The location where the signal was observed. The location is a string that includes the name of the city and the state/province.
Device Type: The type of RF device used to generate the signal. Possible options include HackRF, Halow-U, and - - SteamDeck.
Antenna Type: The type of antenna used to transmit the signal. Possible options include Omnidirectional, Directional, - Dipole, and Yagi.
Temperature: The temperature at the location of the signal observation in degrees Celsius.
Humidity: The relative humidity at the location of the signal observation as a percentage.
Wind Speed: The speed of the wind at the location of the signal observation in kilometers per hour (km/hr).
Precipitation: The amount of precipitation at the location of the signal observation in millimeters (mm).
Weather Condition: The weather condition at the location of the signal observation. Possible options include Sunny, Rainy, and Cloudy.
Interference Type: The type of interference present in the environment. Possible options include None, Co-channel, Adjacent-channel, and Intermodulation.
Battery Level: The remaining battery level of the device used to generate the signal as a percentage.
Power Source: Whether the device used to generate the signal is currently plugged into a power source or not.
CPU Usage: The percentage of the CPU usage of the device used to generate the signal.
Memory Usage: The percentage of the memory usage of the device used to generate the signal.
WiFi Strength: The strength of the WiFi signal at the location of the signal observation in dBm.
Disk Usage: The percentage of the disk usage of the device used to generate the signal.
System Load: The system load of the device used to generate the signal.
Latitude: The latitude of the location of the signal observation.
Longitude: The longitude of the location of the signal observation.
Altitude(m): The altitude of the location of the signal observation in meters.
Air Pressure: The air pressure at the location of the signal observation in hectopascals (hPa).
Device Status: The current status of the device used to generate the signal. Possible options include Streaming I/Q data, Transmitting beacon signal, and Running game.
I/Q Data: The in-phase and quadrature components of the signal as a complex valued array.
The generated dataset can be used for various types of analysis and predictive analysis, which can help machine learning scientists in developing and testing models for RF signal processing, interference detection and mitigation, and device performance optimization. Some of the possible analysis and predictive analysis that can be performed using this data are:

Signal Classification: The dataset can be used to classify RF signals based on their modulation type, frequency, bandwidth, and other features. This can help in identifying specific types of signals, such as voice or data transmissions, and can aid in tasks such as signal detection, interception, and decoding.

Interference Detection: The dataset contains information about the type and level of interference present in the environment. This can be used to develop models for detecting and mitigating interference, which can improve the overall quality of the RF signal.

Device Performance Optimization: The dataset includes information about the type of RF device used to generate the signal, as well as its CPU usage, memory usage, and battery level. This can be used to develop models for optimizing the performance of RF devices, such as reducing power consumption or improving signal quality.

Weather Condition Analysis: The dataset provides information about the weather conditions at the time of signal observation, including temperature, humidity, wind speed, precipitation, and weather condition. This can be used to analyze the impact of weather conditions on RF signal propagation and to develop predictive models for signal behavior under different weather conditions.

Geolocation: The dataset includes latitude and longitude information for each signal observation. This can be used to develop models for geolocation of RF signals, which can aid in tasks such as tracking and surveillance.

Overall, the generated dataset provides a rich source of data for machine learning scientists to develop and test models for various RF signal processing and analysis tasks. The dataset's diverse features make it suitable for a wide range of research and development applications.
