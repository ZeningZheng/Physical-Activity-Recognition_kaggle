# Physical-Activity-Recognition_kaggle
Recognizing daily physical activity from phone sensor signals

This is a group project for the course Big Data Analytics that I worked on with two other students during my masters.
https://www.kaggle.com/c/bda-2021-physical-activity-recognition

#### Aim
Build a classifier that recognizes different types of physical activity from signals measured by the accelerometer and gyroscope in smartphone, which both measure aspects of movement and orientation. 

#### Data
The data for this competition were collected in a lab using a basic smartphone in experiments with human participants carrying out various daily activities in set order.

The experiments were carried out with a group of 30 volunteers within an age bracket of 19-48 years. They performed a protocol of activities composed of six basic activities: three static postures (standing, sitting, lying) and three dynamic activities (walking, walking downstairs and walking upstairs). The experiment also included postural transitions that occurred between the static postures. These are: stand-to-sit, sit-to-stand, sit-to-lie, lie-to-sit, stand-to-lie, and lie-to-stand. All the participants were wearing a smartphone (Samsung Galaxy S II) on the waist during the experiment execution. We captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz using the embedded accelerometer and gyroscope of the device. The experiments were video-recorded to label the data manually. 

#### Candidate machine learning methods

#### Features

#### Statistical features
* **Power:** represents the average squared amplitude of the signal.
* **Energy:** the “total power” of the n samples.
* **Entropy:** a measure of average surprise in handling signals: ‘Surprise’ about an observed value can be expressed in terms of the negative logarithm of the probability of that outcome; the higher the probability, the less ‘surprised’ you are.
* **Mean**
* **Median**
* **Min and max**
* **Mean absolute deviation**
* **Correlation**

#### Time domain features:
* **Cosine angle:** the scaled inner product. This time domain feature takes the ordering of the sequence of numbers into account.
* **Lagged correlation**

#### Frequency domain features:
* **Mean frequency:** the sum of the product of the spectrogram intensity (in dB) and the frequency, divided by the total sum of spectrogram intensity.
* **Standard deviation:** a measure for how much the frequencies in a spectrum can deviate from the centre of gravity.
* **Spectrum peak**
* **Skewness:** a measure for how much the shape of the spectrum below the centre of gravity is different from the shape above the mean frequency.
* **Kurtosis:** provides a measure of the “peakedness” of a random signal.

#### Models
+ Logistic regression, LDA, QDA, K-NN
