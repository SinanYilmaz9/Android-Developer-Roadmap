# Android Developer Roadmap 2022
This repo was created with the goal of being an up-to-date roadmap for Android developers.

- **Languages :earth_africa:**<br />
    _Programming languages used in development._
    - [Kotlin](https://kotlinlang.org/)
    - [Java](https://www.java.com/)
    - [C++](https://www.java.com/)
- **Android Packages :package:**<br />
    _Android Package is the Android application package file format._
    - [AAB](https://developer.android.com/guide/app-bundle)
    - [APK](https://developer.android.com/google/play/expansion-files)
- **Android Studio :house:**<br />
    _Android Studio is the official integrated development environment (IDE)._
    - [Debugger](https://developer.android.com/studio/debug)
    - [CPU Profiler](https://betterprogramming.pub/improve-apps-performance-with-android-profilers-edb240deeb71)
    - [Android Debug Bridge](https://developer.android.com/studio/command-line/adb)
    - [Emulator](https://developer.android.com/studio/run/emulator)
    - [SDK Manager](https://developer.android.com/studio/intro/update#sdk-manager)    
- **Android Manifest :scroll:**<br /> 
    _The manifest file describes essential information about your app to the Android build tools, the Android operating system._
    - [Permissions](https://developer.android.com/guide/topics/manifest/manifest-intro#perms)
    - [App Components](https://developer.android.com/guide/topics/manifest/manifest-intro#components) 
    - [Package](https://developer.android.com/guide/topics/manifest/manifest-intro#package-name)   
- **App Components :basecamp:**<br />
    _App components are the essential building blocks of an Android app._
    - [Activity](https://developer.android.com/reference/android/app/Activity)
    - [Service](https://developer.android.com/reference/android/app/Service)
    - [Broadcast Receiver](https://developer.android.com/reference/android/content/BroadcastReceiver)
    - [Intent](https://developer.android.com/reference/android/content/Intent)
    - [Content Providers](https://developer.android.com/guide/topics/providers/content-providers?hl=en)
- **User Interface :art:**<br />
    _Your app's user interface is everything that the user can see and interact with._ 
    - UI Layouts
        - [ConstraintLayout](https://medium.com/exploring-android/exploring-the-new-android-constraintlayout-eed37fe8d8f1)
        - [MotionLayout](https://developer.android.com/training/constraint-layout/motionlayout)
        - [LinearLayout](https://developer.android.com/guide/topics/ui/layout/linear)
        - [RelativeLayout](https://developer.android.com/guide/topics/ui/layout/relative)
        - [FrameLayout](https://developer.android.com/reference/android/widget/FrameLayout)
    - Styles
        - [Styles vs Themes](https://medium.com/androiddevelopers/android-styling-themes-vs-styles-ebe05f917578)
        - [Dark Theme](https://developer.android.com/guide/topics/ui/look-and-feel/darktheme) 
    - Animations
        - [Material Motion](https://material.io/develop/android/theming/motion)
        - [Transition](https://developer.android.com/training/transitions)  
        - [Object Animator](https://developer.android.com/guide/topics/graphics/prop-animation#object-animator)
        - [Lottie](https://github.com/airbnb/lottie-android)         
- **Architecture :building_construction:**<br />
    _App architecture is an important consideration for ensuring that your apps are robust, testable, and maintainable._
    - [MVVM](https://www.toptal.com/android/android-apps-mvvm-with-clean-architecture)
    - [MVI](https://www.raywenderlich.com/817602-mvi-architecture-for-android-tutorial-getting-started)
    - [MVP](https://www.raywenderlich.com/7026-getting-started-with-mvp-model-view-presenter-on-android)
    - Dependency Injection
        - [Hilt](https://developer.android.com/jetpack/androidx/releases/hilt)
        - [Dagger](https://dagger.dev/dev-guide/)
        - [Koin](https://insert-koin.io/docs/reference/introduction)
        - [Kodein](https://docs.kodein.org/kodein-di/7.10/index.html)           
- **Jetpack :rocket:**<br />
    _Jetpack is a collection of Android software components which helps us in building great Android apps._
    - [Material Design](https://material.io/develop/android)
    - [Architecture Components](https://medium.com/exploring-android/exploring-the-new-android-architecture-components-c33b15d89c23)
    - [Navigation](https://developer.android.com/guide/navigation/)
        - [NavigationUI](https://medium.com/androiddevelopers/navigationui-d21fd4f5c318) 
        - [Graphs and Deep Link](https://www.raywenderlich.com/4332831-navigation-component-for-android-part-2-graphs-and-deep-links)      
    - [Fragment](https://developer.android.com/jetpack/androidx/releases/fragment)           
- **Image Loading :framed_picture:**<br />
    _Image loading libraries make it simple to fetch, decode, and display images._
    - [Glide](https://bumptech.github.io/glide/)
    - [Coil](https://github.com/coil-kt/coil)
    - [Picasso](https://square.github.io/picasso/)
- **Network :fire:**<br />
    _Networking transactions._
    - [Retrofit](https://howtodoandroid.com/retrofit-android-example-kotlin/)
    - [OkHttp](https://square.github.io/okhttp/)
    - [Ktor](https://ktor.io/docs/welcome.html)
    - Conventers
        - [Kotlin Serialization](https://github.com/Kotlin/kotlinx.serialization)
        - [Gson](https://github.com/google/gson)
        - [Moshi](https://github.com/square/moshi)     
- **Local Storage :floppy_disk:**<br />
    _Local storage is the storage of the private data on the device memory._
    - [SharedPreferences](https://developer.android.com/training/data-storage/shared-preferences)
    - [SQLite](https://developer.android.com/jetpack/androidx/releases/sqlite)
        - [Room](https://medium.com/mindorks/using-room-database-android-jetpack-675a89a0e942)
        - [SQLDelight](https://cashapp.github.io/sqldelight/android_sqlite/) 
    - [DataStore](https://developer.android.com/topic/libraries/architecture/datastore)
    - [Realm](https://zhuinden.medium.com/how-to-use-realm-for-android-like-a-champ-and-how-to-tell-if-youre-doing-it-wrong-ac4f66b7f149)  
- **Asynchronous :twisted_rightwards_arrows:**<br />
   _An asynchronous task is defined by a computation that runs on a background thread and whose result is published on the UI thread._ 
   - [Thread](https://blog.mindorks.com/android-core-looper-handler-and-handlerthread-bd54d69fe91a)
   - [Coroutines](https://medium.com/androiddevelopers/coroutines-on-android-part-i-getting-the-background-3e0e54d20bb)
   - RX
        - [RXJava](https://www.toptal.com/android/functional-reactive-android-rxjava)
        - [RXKotlin](https://www.baeldung.com/kotlin/rxkotlin)
        - [RXAndroid](https://www.androidhive.info/RxJava/android-getting-started-with-reactive-programming/)       
   - [WorkManager](https://developer.android.com/topic/libraries/architecture/workmanager) 
- **Service :battery:**<br />
   - Google
        - [Google Play Services](https://developers.google.com/android/guides/setup)
        - [Google Maps](https://developers.google.com/maps/documentation/android-sdk/overview)
   - Huawei
        - [Huawei Mobile Services](https://developer.huawei.com/consumer/en/hms)
        - [Huawei Map Kit](https://developer.huawei.com/consumer/en/hms/huawei-MapKit/)
   - [Firebase](https://firebase.google.com/docs)
   - [AppGallery Connect](https://developer.huawei.com/consumer/en/agconnect/)
   - Advertisement
        - [Google Admob](https://admob.google.com/home/)
        - [Huawei Ads](https://developer.huawei.com/consumer/en/huawei-ads/)
        - [MoPub](https://www.mopub.com/en) 
- **Compose :label:**<br />
    _Jetpack Compose is Android's modern toolkit for building native UI._
    - [Compose Basics](https://developer.android.com/codelabs/jetpack-compose-basics)
    - [Compose Navigation](https://developer.android.com/codelabs/jetpack-compose-navigation)
    - [Layouts in Compose](https://developer.android.com/codelabs/jetpack-compose-layouts)    
    - [Migrating to Compose](https://developer.android.com/codelabs/jetpack-compose-migration) 
    - [Compose Animation](https://developer.android.com/codelabs/jetpack-compose-animation)   
- **Build System :smoking:**<br />
    _The Android build system compiles app resources and source code and packages them into APKs or Android App Bundles._
    - [Gradle Build System](https://www.raywenderlich.com/249-gradle-tutorial-for-android-getting-started)      
- **Security :closed_lock_with_key:**<br />
    _Android has built-in security features that significantly reduce the frequency and impact of application security issues._
    - [ProGuard](https://blog.mindorks.com/applying-proguard-in-an-android-application)
    - [R8](https://betterprogramming.pub/r8-shrinking-in-android-27f3edbbad9e)
    - [Keystore](https://developer.android.com/training/articles/keystore)  
- **Test :test_tube:**<br />
    _Testing is an integral part of the app development process._
    - [Unit Tests](https://betterprogramming.pub/android-unit-testing-basics-3e7075a432a1)
    - [Integration Tests](https://medium.com/airbnb-engineering/writing-fast-deterministic-and-accurate-android-integration-tests-c56811bd14e2)
    - [Instrumentation Tests](https://developer.android.com/training/testing/instrumented-tests)                     
- **CI/CD :satellite:**<br />
   _CI/CD is the combined practice of continuous integration (CI) and either continuous delivery or continuous deployment (CD)._
   - [GitHub Actions](https://docs.github.com/en/actions)
   - [Travis CI](https://docs.travis-ci.com/)
   - [Bitrise](https://devcenter.bitrise.io/)
   - [Jenkins](https://www.jenkins.io/doc/)
   - [Circle CI](https://circleci.com/docs/)
- **QA & Publishing :shopping_cart:**<br />
   _Publishing is the general process that makes your Android applications available to users._
   - [Firebase App Distribution](https://firebase.google.com/docs/app-distribution)
   - [AppGallery Connect - Open Testing](https://developer.huawei.com/consumer/en/doc/development/AppGallery-connect-Guides/agc-betatest-introduction-0000001071477284)
   - [Google Play Store](https://play.google.com/console/about/)   
   - [App Gallery](https://developer.huawei.com/consumer/en/appgallery/)  
