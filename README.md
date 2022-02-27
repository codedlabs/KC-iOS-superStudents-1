# مصفوفة من الكائنات

## * عمل struct

#### تعريف struct بوضع الاسم ٫ بهذه الطريقة 

```
struct NewStruct {
                 ……
                 ……
                }
```




## * عمل الخصائص properties لل struct


#### طريقة عمل الخصائص هكذا ٫ ووضع النوع لكل properties

```
struct NewStruct {
         var prop1 : String
         var prop2 : Int
           }
```



## عمل المصفوفة array


#### تعريف متغير ليكون مصفوفة تحتوي على كائنات من struct التي تم تعريفها ٫ بهذه الطريقة 



```
var NewArray = [NewStruct(prop1: "a", prop2: 1), NewStruct(pror1: "b", pror2: 2)]
```



---

#### تمرين


### قم بعمل fork من رابط gitHub .

#### 1. قم بإنشاء تطبيق جديد في XCode
#### 2. قم بعمل struct بإسم CoronaDetails 
#### 3. قم بعمل خصائص لهذا struct بهذه الاسماء كمتغيرات :

 <p align="right"> 
fullName - area - numberOfDoses
</p>



#### 4. قم بعمل متغير كمصفوفة من نوع الكائن لهذا ال struct بإسم CoronaNewCases
#### 5. قم بعرض هذه الأسماء على صفحة التطبيق كما هو موضح في الصورة
### ملاحظة : بالمرفق ستجد الصورة الخضراء كورونا . او يمكنك اضافة أي صورة أخرى



<p align="center">
<img width="291" alt="corona App" src="https://user-images.githubusercontent.com/60436597/155864966-0d2950db-0ba4-41fa-8407-1fac1be46ea9.png">
</p>
