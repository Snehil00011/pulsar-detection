### Important Links
* https://www.kaggle.com/datasets/colearninglounge/predicting-pulsar-starintermediate/data
* https://datauab.github.io/pulsar_stars
* htru2 official dataset: https://archive.ics.uci.edu/dataset/372/htru2
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