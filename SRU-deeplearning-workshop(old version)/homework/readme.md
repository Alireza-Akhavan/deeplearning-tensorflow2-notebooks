<div dir="rtl">

# قسمت 1
## تمرین شبکه های تمام متصل یا dense یا fully connected

### تمرین 1-1:

[ex1-mlp-iris.ipynb](https://nbviewer.jupyter.org/github/alireza-akhavan/SRU-deeplearning-workshop/blob/master/homework/ex1-mlp-iris.ipynb)


*لطفا برای  سوال ۱ همین مخزن کد به آدرس [SRU-deeplearning-workshop](https://github.com/Alireza-Akhavan/SRU-deeplearning-workshop) را از گیت هاب دانلود کرده و سلول های خالی را در کامپیوتر خودتان تکمیل کنید.

کد این سوال در پوشه  [homework](https://github.com/Alireza-Akhavan/SRU-deeplearning-workshop/tree/master/homework) است.  

### تمرین 1-2

یک طبقه بند برای دیتاست Fashion MNIST بنویسید.

این دیتاست قبلا در کراس موجود است و کافی است با دستور:
</div>

```python

fashion_mnist = keras.datasets.fashion_mnist
(train_images, train_labels), (test_images, test_labels) = fashion_mnist.load_data()

```

<div dir="rtl">

لود کنید
سپس:

الف: تعداد کلاس ها را چاپ کنید

ب: چند تصویر از این دیتاست را نمایش دهید

ج: داده را نرمال کرده و مناسب آموزش برای یک شبکه عصبی آماده کنید


د: یک شبکه تمام متصل (FC) آموزش دهید.

:sparkles:راهنمایی:sparkles:

سعی کنید خودتان انجام دهید. اما صورت مشکل میتوانید از راهنمای 
[این لینک](https://www.tensorflow.org/tutorials/keras/classification)
استفاده کنید



# قسمت 2
## تمرین شبکه های کانولوشنالی  یا Convolutional neural network

### کوییز

لطفا کوئیز زیر را حل کرده و مدرک ان را  ارسال کنید:

[https://www.proprofs.com/quiz-school/story.php?title=mjm5odizmgit76](https://www.proprofs.com/quiz-school/story.php?title=mjm5odizmgit76)

توجه: به دلیل به هم ریختن راست به چپ سالات در پلتفرم سوالات، میتوانید هر سوال را در یک پردازشگر متنی کپی کرده و راست به چپ کنید سپس بخوانید

### تمرین 2-1:

همانند  تمرین 1-1 در پوشه ی [homework](https://github.com/Alireza-Akhavan/SRU-deeplearning-workshop/tree/master/homework)
یک فایل با نام
[ex2-conv-cifar10-in-colab.ipynb](https://nbviewer.jupyter.org/github/alireza-akhavan/SRU-deeplearning-workshop/blob/master/homework/ex2-conv-cifar10-in-colab.ipynb)

وجود دارد. لطفا روی آن تغییراتی که صورت سوال مطرح کرده را انجام بدید و سپس ارسال کنید.

برای یادگیری با گوگل کولب طبق لینک در نوت بوک لطفا آن را در کولب اجرا و حل کنید

### تمرین 2-2:


در ادامه ی سوالات  تمرین 1-2
یک طبقه بند کانولوشنالی برای دیتاست Fashion MNIST بنویسید.



# قسمت 3
## تمرین کالبک ها در کراس یا callbacks

:sparkles:

——- برای تمارین مربوط به کالبک  دو ویدیوی زیر را ببینید ——

</div>

[https://www.aparat.com/v/Tdbck](https://www.aparat.com/v/Tdbck)

[https://www.aparat.com/v/r05IW](https://www.aparat.com/v/r05IW)

<div dir="rtl">

### تمرین 3-1:

برای یکی از مدل‌هایی که قبلا در کلاس آموزش دادیم، مثل مثال هدی،
تنسربورد(Tensorboard) را فعال کنید، و از نمودار فرایند آموزش، و همچنین هیستوگرام لایه ها عکس بگیرید و تصاویر به همراه کد نهایی را ارسال کنید.

### تمرین 3-2:

برای کد شماره 6 (آموزش روی دیتای هدی) 
بهتریت LR را پیدا کنید و نوت بوک کد نهایی را به همراه پاسخ بفرستید.
بدین منظور از کالبک مخصوصش استفاده کنید

### تمرین 3-3:

یک کالبک ساده بنویسید که اگر دقت validation-dataی validation نوت بوک شماره 6 
[06_ConvolutionalNeuralNetwork-Hoda-Keras.ipynb](nbviewer.jupyter.org/github/Alireza-Akhavan/SRU-deeplearning-workshop/blob/master/06_ConvolutionalNeuralNetwork-Hoda-Keras.ipynb)
یا هر کدی که به انتخاب خودتان صلاح میدانید
به 75 رسید، آموزش مدل متوقف شود.

</div>

<div dir="rtl">

# قسمت 4

### تمرین 4-1:

  
از یکی از شبکه‌های از قبل آموزش داده شده استفاده کنید، و کدی بنویسید که وبکم را سمت هر شیئی میگیریم؛ نام آن را در تصویر بنویسد.
راهنمایی:
برای این تمرین از نوت بوک شماره 10 مخزن SRU-deeplearning-workshop
و کدهای 4 (برای نوشتن روی عکس)  و 18 (برای استفاده از وبکم) مخزن class.vision 
باید استفاده کنید.

برای این تمرین به جای کد، بهتر است یک فیلم 30 ثانیه ای از عملکرد برنامه بفرستید.



### تمرین 4-2:

یک طبقه بند برای طبقه نبدی تصاویر گل بنویسید.
اگر میخواهید در کامپیوتر خودتان آموزش بدید، دیتاست را از آدرس

[http://colab.class.vision/flower_photos.tgz](http://colab.class.vision/flower_photos.tgz)

دانلود کنید.

و اگر مخواهید در گوگل کولب آموزش دهید،
با دستور

</div>

```python

flowers_root = tf.keras.utils.get_file(
    'flower_photos',
    'https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz',
    untar=True)
```

<div dir="rtl">

دیتاست از سرور گوگل دانلود شده، و مسیر در پوشه ای با نام  
flowers_root
 نوشته می‌شود.

برای این کار نیز خودتان با هر معماری که دوست دارید شبکه را طراحی کنید.
  
  
### تمرین 4-3:

ویدیوی
[https://www.aparat.com/v/HGvC2](https://www.aparat.com/v/HGvC2)
را ببینید، و  مثال طبقه بندی گربه و سک در نوت بوک 7 یا 8 به انتخاب خودتان در مخزن SRU-deeplearning-workshop را به جای datagenerator کراس با tf dada بازنویسی کنید.
سعی کنید نکات افزایش سرعت را استفاده کنید

توصیه شدید میشود این سوال را در گوگل کولب حل کنید.

با دستورات زیر می‌توانید دیتاست را از سرور گوگل به کولب انتقال داده، از زیپ خارج کنید و در نهایت در دو متغیر، مسیر فایل های آموش و ولیدیشن را داشته باشید:

</div>

```python

import tensorflow as tf
import os

_URL = 'https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip'

path_to_zip = tf.keras.utils.get_file('cats_and_dogs.zip', origin=_URL, extract=True)

PATH = os.path.join(os.path.dirname(path_to_zip), 'cats_and_dogs_filtered')

train_dir =  "/root/.keras/datasets/cats_and_dogs_filtered/train"
validation_dir = "/root/.keras/datasets/cats_and_dogs_filtered/validation"

```


