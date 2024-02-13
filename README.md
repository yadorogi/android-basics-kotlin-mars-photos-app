MarsPhotos - Solution Code
==================================

Solution code for Android Basics in Kotlin.

Introduction
------------

[EN]

MarsPhotos is a demo app that shows actual images of Mar's surface. These images are
real-life photos from Mars captured by NASA's Mars rovers. The data is stored on a Web server
as a REST web service.  This app demonstrated the use of [Retrofit](https://square.github.io/retrofit/) to make REST requests to the web service, [Moshi](https://github.com/square/moshi) to
handle the deserialization of the returned JSON to Kotlin data objects, and [Coil](https://coil-kt.github.io/coil/) to load images by URL.

[JP]

MarsPhotosは、火星表面の実際の画像を表示するデモアプリです。

これらの画像は、NASAの火星探査機が撮影した火星の実際の写真で、データはRESTウェブサービスとしてウェブサーバーに保存されています。

このアプリでは、[Retrofit](https://square.github.io/retrofit/) を使ってウェブサービスにRESTリクエストを行い、

[Moshi](https://github.com/square/moshi) を使って返されたJSONをKotlinデータオブジェクトにデシリアライズし、

[Coil](https://coil-kt.github.io/coil/) を使ってURLで画像を読み込むことをデモしました。



The app also leverages [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel),
[LiveData](https://developer.android.com/topic/libraries/architecture/livedata), and
[Data Binding](https://developer.android.com/topic/libraries/data-binding/) with binding 
adapters.

Pre-requisites
--------------

You need to know:
- How to create and use fragments.
- How to use architecture components including ViewModel, and LiveData.
- How to use coroutines for long-running tasks.


Getting Started
---------------

1. Download and run the app.
