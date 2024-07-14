### Important Links
* https://www.kaggle.com/datasets/colearninglounge/predicting-pulsar-starintermediate/data
* https://datauab.github.io/pulsar_stars
* htru2 official dataset: https://archive.ics.uci.edu/dataset/372/htru2
* Balancing and Genetic programming Research Paper: https://www.sciencedirect.com/science/article/abs/pii/S2213133724000167
### Importing HTRU1 (PyTorch)
```python
from torchvision import datasets
import torchvision.transforms as transforms
from htru1 import HTRU1
```
### Importing HTRU2
Required Libraries:
```
pip install ucimlrepo
```
Code:
```python
from ucimlrepo import fetch_ucirepo 
  
# fetch dataset 
htru2 = fetch_ucirepo(id=372) 
  
# data (as pandas dataframes) 
X = htru2.data.features 
y = htru2.data.targets 
  
# metadata 
print(htru2.metadata)

# variable information 
print(htru2.variables) 

```
### Email ID and Password
email: pulsardetectionisro@gmail.com
pass: isro@123


### Time Intervals
The time interval for a single pulsar profile in the HTRU1 and HTRU2 datasets is typically determined by the sampling rate used during data collection. Here is a general explanation based on typical practices in pulsar surveys, as specific details for HTRU1 and HTRU2 were not found in the provided document:

Time Interval for a Single Pulsar Profile
Sampling Rate (tsamp): Pulsar data is collected at specific intervals, known as the sampling rate, which is usually in microseconds (µs). The sampling rate is chosen to maximize sensitivity to the signals being searched for.

Observational Period (tobs): This is the total duration over which the data is collected for each observation, typically in seconds.

Frequency Channels (nchans): The data is split into multiple frequency channels, and the total number of samples (stot) for each channel is the observational period divided by the sampling rate (stot = tobs / tsamp).

General Example
For example, if the sampling rate (tsamp) is 64 µs and the observational period (tobs) is 600 seconds, the total number of samples (stot) would be:

𝑠𝑡𝑜𝑡 = 𝑡𝑜𝑏𝑠/𝑡𝑠𝑎𝑚𝑝 = 600 seconds/64 µs = 9375000 samples

Each pulsar profile would be constructed from these samples, representing the signal collected over the 600-second period at the given sampling rate.

HTRU1 and HTRU2 Specifics
While the exact values for HTRU1 and HTRU2 may differ, they would generally follow this pattern. The sampling rates and observational periods are chosen based on the requirements of the survey and the characteristics of the pulsars being targeted.

If you have access to more detailed documentation or specific values for HTRU1 and HTRU2, those details would provide the precise time intervals used in these datasets. Otherwise, the general principles outlined here would apply.






