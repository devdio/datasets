## Fahsion-mnist
- 클래스명
```python
class_names = ['T-shirt/top', 'Trouser', 'Pullover', 'Dress', 'Coat', 
'Sandal', 'Shirt', 'Sneaker', 'Bag', 'Ankle boot']
```
- 이미지 표시 
```
samples = np.random.randint(len(X_train), size=9) 
samples

plt.figure(figsize = (8, 6))
for i, idx in enumerate(samples):
    plt.subplot(3, 3, i+1)
    plt.xticks([])
    plt.yticks([])
    plt.imshow(X_train[idx], cmap = 'gray')
    plt.title(class_names[y_train[idx]])
plt.show()
```
## cifar-10
- 클래스명
```
class_names = ['airplane', 'automobile', 'bird', 'cat', 'deer', 
               'dog', 'frog', 'horse', 'ship', 'truck']
```


## 캐글

- Titanic
https://www.kaggle.com/code/startupsci/titanic-data-science-solutions

- Health Insurance Cost Predicition
https://www.kaggle.com/datasets/mirichoi0218/insurance

- House Price Prediction
https://www.kaggle.com/code/ibrohimsharipov/house-price-prediction

- 100,000 UK Used Car Data set
https://www.kaggle.com/datasets/adityadesai13/used-car-dataset-ford-and-mercedes


## 판다스 참조
- 리스트 
```
doc = [['Joe', 20, 85.10, 'A', 'Swimming'],
        ['Nat', 21, 77.80, 'B', 'Reading'],
        ['Harry', 19, 91.54, 'A', 'Music'],
        ['Sam', 20, 88.78, 'A', 'Painting'],
        ['Monica', 22, 60.55, 'B', 'Dancing']]

c_name = ['Name', 'Age', 'Marks', 'Grade', 'Hobby']
idx = ['s1', 's2', 's3', 's4', 's5']

```
- 딕서너리
```

- 딕셔너리
doc = {'Name' :['Joe','Nat','Harry','Sam','Monica',],
        'Age':[20, 21, 19, 20, 22],
        'Marks':[85.10, 77.80, 91.54, 88.78, 60.55],
        'Grade':['A', 'B', 'A', 'A', 'B',],
        'Hobby':['Swmming', 'Reading', 'Music', 'Painting', 'Dancing']}
```
- merge()함수
```
shop = { 'Shop_id' : ['SP01', 'SP02', 'SP03', 'SP04'],
        'City' : ['Chennai', 'Madurai', 'Trichy', 'Coimbatore'],
        'ZipCode' : [600001, 625001, 620001, 641001] }

product = { 'Shop_id' : ['SP01', 'SP02', 'SP02', 'SP03', 'SP03', 'SP03', 'SP05'],
           'product_id' : ['p01', 'p02', 'p03', 'p01', 'p02', 'p03', 'p02'],
           'price' : [220, 500, 145, 225, 510, 150, 505] }
```

## 데이터 설명
```
- BASE : https://drive.google.com/uc?id=
- Cats_and_Dogs_Filtered.zip : 
    * https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip
- HumanActivity Recognition : 
    * https://drive.google.com/uc?id=1ypa5iZ1dLDO-zGRO_yDXrJnMvjRGUG4v
- rps : 
    * https://storage.googleapis.com/laurencemoroney-blog.appspot.com/rps.zip
    * https://storage.googleapis.com/laurencemoroney-blog.appspot.com/rps-test-set.zip
- BBRegression:
    * https://drive.google.com/uc?id=1-RBvPOYycsSpS7rVP0Pqwcbh18lZYDeb
```
