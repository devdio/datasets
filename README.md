### matplotlib의 한글화 문제
- [koreanize-matplotlib](https://github.com/ychoi-kr/koreanize-matplotlib)

# 테스트용 데이터셋

## churn_bank.csv
```
*  CustomerId: 데이터 세트 내에서 개별 고객을 추적하고 차별화하는 데 사용할 수 있습니다.
*  Surname: 이름
*  CreditScore: 신용도 평가
*  Geography: 지역
*  Gender: 성별
*  Age: 나이
*  Tenure: 일반적으로 고객이 은행과 거래한 연도 또는 개월 수를 나타냅니다.
*  Balance: 특정 시점에 고객의 은행 계좌에 있는 금액을 반영합니다
*  NumOfProducts: 상품의 개수
*  HasCrCard: 신용카드를 가지고 있는지 아닌지 
*  IsActiveMember: 활성 회원(1)인지 아닌지(0)
*  EstimatedSalary: 고객의 소득 수준에 대한 근사치
*  Exited: 고객이 은행에서 이탈했는지(1) 또는 이탈하지 않았는지(0)
```

## Maplotlib 의 한글화문제 해결 
- [https://github.com/ychoi-kr/koreanize-matplotlib](https://github.com/ychoi-kr/koreanize-matplotlib)

## gdown의 권한 문제
```
!pip install --upgrade --no-cache-dir gdown
```  


## 데이터 설명
```
!pip install --upgrade --no-cache-dir gdown
```  
  
```
- BASE : https://drive.google.com/uc?id=  


- human horse
   - https://www.tensorflow.org/datasets/catalog/horses_or_humans

- rps : 
    * https://storage.googleapis.com/laurencemoroney-blog.appspot.com/rps.zip
    
- flowers
  * https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz  

- baby_sounds
  * https://drive.google.com/u/0/uc?id=1j3bpHIzX-SECXJgsOkssypXEuAeyRJ26

- Cats_and_Dogs_Filtered.zip : 
    * https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip
    
- Mask Detection :
   * https://drive.google.com/uc?id=12FIGFL_-WnKTTOo8AC_eh3O1VNzvDeQP

- HumanActivity Recognition : 
    * https://drive.google.com/uc?id=1ypa5iZ1dLDO-zGRO_yDXrJnMvjRGUG4v  
    
- rps : 
    * https://storage.googleapis.com/laurencemoroney-blog.appspot.com/rps.zip
     

- BoundingBox Sample
  * https://drive.google.com/uc?id=1jNlnTFMzxaxZ799JcvVnN_aHsx1O3OeL

- labelImg exe
   * https://github.com/heartexlabs/labelImg/releases

- BBRegression (roboflow):
    * https://drive.google.com/uc?id=1-RBvPOYycsSpS7rVP0Pqwcbh18lZYDeb

- Image Localization Dataset
  * https://www.kaggle.com/datasets/mbkinaci/image-localization-dataset

- Audio Mnist
  * https://github.com/Jakobovski/free-spoken-digit-dataset

- Facial Keypoints Detection (kaggle)
  * https://drive.google.com/uc?id=1Ee3qKH7aUpB3eUQP-nUiJyJECoTzVAU1
  
- GTSRB
  * https://drive.google.com/uc?id=17rL7t_ltHtSvKtbRQcmx9jGlFDTlF4ao
  
-  kaggle rps
  * https://drive.google.com/drive/folders/11wq57w-fi-mEzK4iC1DDS24IXbqe-q6t?usp=sharing
  * https://drive.google.com/uc?id=1dXD4MIzHgJ31xVGfDdBx0cgwZs1_W589  
   
```

## GTSRB
```
# Label Overview
classes = { 0:'Speed limit (20km/h)',
            1:'Speed limit (30km/h)', 
            2:'Speed limit (50km/h)', 
            3:'Speed limit (60km/h)', 
            4:'Speed limit (70km/h)', 
            5:'Speed limit (80km/h)', 
            6:'End of speed limit (80km/h)', 
            7:'Speed limit (100km/h)', 
            8:'Speed limit (120km/h)', 
            9:'No passing', 
            10:'No passing veh over 3.5 tons', 
            11:'Right-of-way at intersection', 
            12:'Priority road', 
            13:'Yield', 
            14:'Stop', 
            15:'No vehicles', 
            16:'Veh > 3.5 tons prohibited', 
            17:'No entry', 
            18:'General caution', 
            19:'Dangerous curve left', 
            20:'Dangerous curve right', 
            21:'Double curve', 
            22:'Bumpy road', 
            23:'Slippery road', 
            24:'Road narrows on the right', 
            25:'Road work', 
            26:'Traffic signals', 
            27:'Pedestrians', 
            28:'Children crossing', 
            29:'Bicycles crossing', 
            30:'Beware of ice/snow',
            31:'Wild animals crossing', 
            32:'End speed + passing limits', 
            33:'Turn right ahead', 
            34:'Turn left ahead', 
            35:'Ahead only', 
            36:'Go straight or right', 
            37:'Go straight or left', 
            38:'Keep right', 
            39:'Keep left', 
            40:'Roundabout mandatory', 
            41:'End of no passing', 
            42:'End no passing veh > 3.5 tons' }
```

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


