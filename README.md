# Data Mining with Python

![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/Django.svg)

Anaconda: https://www.anaconda.com/products/individual

VS Code: https://code.visualstudio.com

Xcode: https://developer.apple.com/xcode

Jupyter: https://jupyter.org

any suggestions or feedback write to me [here](https://github.com/yasinnaal/python-data-mining/issues)

---

### Check two images similarity

![anytext](https://github.com/yasinnaal/images/blob/main/bb_reuslt.png)

```python
from PIL import Image
import imagehash

hash1 = imagehash.average_hash(Image.open('bike.jpg')) 
hash2 = imagehash.average_hash(Image.open('bike.jpg')) 
cutoff = 5

if hash1 - hash2 < cutoff:
  print('image1 average hash value:', hash1)
  print('image2 average hash value:', hash2)  
  print('MATCH -images are similar.')
  
else:
  print('image1 average hash value:', hash1)
  print('image2 average hash value:', hash2)    
  print('NO MATCH - images are not similar !')
```  
<br>
image1: fffff704808390fe<br>

image2: fffff704808390fe<br>

MATCH -images are similar.<br><br>


![anytext](https://github.com/yasinnaal/images/blob/main/bp_reuslt.png)

```python
from PIL import Image
import imagehash

hash1 = imagehash.average_hash(Image.open('panda.jpg')) 
hash2 = imagehash.average_hash(Image.open('bike.jpg')) 
cutoff = 5

if hash1 - hash2 < cutoff:
  print(hash1)
  print(hash2)
  print('MATCH -images are similar.')
else:
  print('image1 average hash value:', hash1)
  print('image2 average hash value:', hash2)    
  print('NO MATCH - images are not similar !.')
```
<br>
image1: 00189c1e1fb4e080 <br>

image2: fffff704808390fe <br>

NO MATCH - images are not similar ! <br><br>


![anytext](https://github.com/yasinnaal/images/blob/main/pp_reuslt.png)

```python
from PIL import Image
import imagehash

hash1 = imagehash.average_hash(Image.open('panda.jpg')) 
hash2 = imagehash.average_hash(Image.open('panda.jpg')) 
cutoff = 5

if hash1 - hash2 < cutoff:
  print(hash1)
  print(hash2)
  print('MATCH -images are similar.')
else:
  print('image1 average hash value:', hash1)
  print('image2 average hash value:', hash2)    
  print('NO MATCH - images are not similar !.')
  
```
<br>
image1: 00189c1e1fb4e080 <br>

image1: 00189c1e1fb4e080 <br>

MATCH -images are similar <br><br>


---

# Compare Images - Map Location

**You can apply the same for many challanges like detect the change from the images (Pre.jpg and Post.jpg) of the same map location.**

![](https://github.com/yasinnaal/python-data-mining/blob/main/images-map-location/__results___7_1.png)
![](https://github.com/yasinnaal/python-data-mining/blob/main/images-map-location/__results___10_1.png)
![](https://github.com/yasinnaal/python-data-mining/blob/main/images-map-location/__results___11_1.png)
![](https://github.com/yasinnaal/python-data-mining/blob/main/images-map-location/__results___9_1.png)

---

# Python data mining examples 

- [SAP bikes store sales analysis](https://github.com/yasinnaal/Python-Data-Mining/blob/main/sap_bikes_store_sales_analysis/sap-bikes-store-sales-analysis.ipynb)<br> SAP bikes store sales analysis with Python

- [Airbnb User Bookings Analysis](https://github.com/yasinnaal/Python-Data-Mining/tree/main/Airbnb-Bookings) <br> Predict user country destination

- [COVID-19 World Vaccination Progress](https://github.com/yasinnaal/Python-Data-Mining/blob/main/COVID19-Vaccination-Progress/covid-19-world-vaccination-progress.ipynb) <br> Which country is using what vaccine? where the vaccination programme is more advanced?

- [Years of experience and salary correlation](https://github.com/yasinnaal/Python-Data-Mining/blob/main/years-of-experience-and-salary-correlation/years-of-experience-and-salary-correlation.ipynb) <br> Predict salary base on years of experience

- [Weather Data History Analysis - Sweden](https://github.com/yasinnaal/Python-Data-Mining/blob/main/weather-data-history-analysis-sweden.ipynb)

- [rolling simulation of two 6 sided dice](https://github.com/yasinnaal/Python-Data-Mining/blob/main/rolling-simulation-of-two-6-sided-dice.ipynb) <br> Practice on Python random library

- [Creating and Manipulating 1D & 2D Arrays](https://github.com/yasinnaal/Python-Data-Mining/blob/main/matrix-multiplication-numpy.ipynb)

<br>

any suggestions or feedback write to me [here](https://github.com/yasinnaal/python-data-mining/issues)

Thanks
