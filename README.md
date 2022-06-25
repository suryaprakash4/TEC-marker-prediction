# TEC-marker-prediction

Predicting atmospheric total electron content predictive markers such as solar flux index by using a regression model based on Lasso regression to eliminate external feature selection.

============================================================================

The Total Electron Content (TEC) is the total number of electrons present along a path between a radio transmitter and receiver. Radio waves are affected by the presence of electrons. The more electrons in the path of the radio wave, the more the radio signal will be affected. For ground to satellite communication and satellite navigation, TEC is a good parameter to monitor for possible space weather impacts.

TEC is measured in electrons per square meter. By convention, 1 TEC Unit TECU = 10^16 electrons/m². Vertical TEC values in Earth’s ionosphere can range from a few to several hundred TECU.

The TEC in the ionosphere is modified by changing solar Extreme Ultra-Violet radiation, geomagnetic storms, and the atmospheric waves that propagate up from the lower atmosphere. The TEC will therefore depend on local time, latitude, longitude, season, geomagnetic conditions, solar cycle and activity, and troposphere conditions. The propagation of radio waves is affected by the ionosphere. The velocity of radio waves changes when the signal passes through the electrons in the ionosphere. The total delay suffered by a radio wave propagating through the ionosphere depends both on the frequency of the radio wave and the TEC between the transmitter and the receiver. At some frequencies the radio waves pass through the ionosphere. At other frequencies, the waves are reflected by the ionosphere.

The change in the path and velocity of radio waves in the ionosphere has a big impact on the accuracy of satellite navigation systems such as GPS/GNSS. Neglecting changes in the ionosphere TEC can introduce tens of meters of error in the position calculations. The Global Positioning System (GPS), the US part of GNSS, uses an empirical model of the ionosphere, the Klobuchar model, to calculate and remove part of the positioning error caused by the ionosphere when single frequency GPS receivers are used. When conditions deviate from those predicted by the Klobuchar model, GPS/GNSS systems will have larger positioning errors
