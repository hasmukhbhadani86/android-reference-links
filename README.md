# Android Reference Links

- Get Started: https://www.tutlane.com/tutorial/android
  - Android App components [Activities, Intents, Content Providers, Broadcast Receivers,Services]
  - Intent, Intent filter, storage types.

- Service: 
  - Overview: https://www.tutlane.com/tutorial/android/android-services-with-examples
  - Service vs Intentservice: https://blog.mindorks.com/service-vs-intentservice-in-android

- Diffence B\W [Service, Thread, IntentService and AsyncTask]
  - https://androidcreativity.wordpress.com/2017/09/02/difference-bw-service-thread-intentservice-and-asynctask/
  - https://medium.com/@varun93342/difference-between-thread-service-and-asynctask-in-android-d6e37960e56c

- Sensor: https://www.javatpoint.com/android-sensor-tutorial 

- Intent Filter: 
  - https://www.tutorialspoint.com/android/android_intents_filters.htm

- Fragments: 
  - Lifecycle:     https://blog.mindorks.com/android-fragments-and-its-lifecycle
  - Add vs Replace: https://stackoverflow.com/questions/18634207/difference-between-add-replace-and-addtobackstack

- Launch Mode:
  - Overview: https://android.jlelse.eu/android-activity-launch-mode-e0df1aa72242
  - Difference B\W [standard ,singleTop, singleTask, singleInstance ]
  - https://stackoverflow.com/questions/25773928/setting-launchmode-singletask-vs-setting-activity-launchmode-singletop

## MVVM Architecture Pattern  
  - Overview https://codingwithmitch.com/blog/getting-started-with-mvvm-android/
  - MVC vs MVP Vs MVVM vs MVI:	https://academy.realm.io/posts/eric-maxwell-mvc-mvp-and-mvvm-on-android/
  - Videos:
    - MVP vs MVVM:	https://www.youtube.com/watch?v=ugpC98LcNqA&t=939s
    - MVVM:	
      - https://www.youtube.com/watch?v=sOrz5GhZNl4&list=PLlxmoA0rQ-LyVuVR1LFvpR1K8A0HsIBYx&index=1
      - https://www.youtube.com/watch?v=R-X2nM3d2FI&list=PLRKyZvuMYSIO0jLgj8g6sADnD0IBaWaw2&index=1
    - MVI:	https://www.youtube.com/watch?v=tIPxSWx5qpk

## Android Jetpack  
  - Overview: https://blog.mindorks.com/what-is-android-jetpack-and-why-should-we-use-it
  - DataBinding: 
    - BindView: https://umangburman.github.io/MVVM-DataBinding-With-LiveData-Login/
    - Bind Error: https://www.journaldev.com/22561/android-mvvm-livedata-data-binding
    - Bind RecyclerView: https://yamikrish.blogspot.com/2018/12/databinding-in-recyclerview-android.html
    - DataBinding vs ViewBinding: https://newbedev.com/android-difference-between-databinding-and-viewbinding  
    - Room:
      - Overview:	https://medium.com/mindorks/android-architecture-components-room-viewmodel-and-livedata-50611793e4a9
      - Source code: https://github.com/smartherd/ArchitectureComponentsRoom  
    - Work Manager:
       - Overview:	https://www.simplifiedcoding.net/android-workmanager-tutorial/
       - Background location update: https://dev.to/bigyan4424/workmanager-for-background-location-updates-fog    

## RetroFit
  - Fundamentals: https://www.youtube.com/watch?v=tPIdWALEVLc&t=946s
  - Example:
    - MVVM, Retrofit: https://www.simplifiedcoding.net/android-viewmodel-using-retrofit/
    - MVVM, Retrofit,DataBinding:  https://androidwave.com/android-data-binding-recyclerview/

## Dagger2
  - Overview: https://androidwave.com/dagger2-android-example/
  - Video: https://www.youtube.com/watch?v=Grzqz-B3NWU

## Dagger Hilt
- Overview: https://blog.mindorks.com/dagger-hilt-tutorial
- PlayList: https://www.youtube.com/playlist?list=PL4EnMCc01RC3i81My4kM2Cf9MZOMwOueo

## Rxjava
  - Overview: https://www.journaldev.com/18948/rxjava-tutorial
  - Parallel & Sequence API call:	https://www.youtube.com/watch?v=vGlyTgIdQQ0
  - MVVM, RX java, Room, Retrofit
    - Video:https://www.youtube.com/watch?v=u0pQQywK7S8&list=PL7CGVRj_4Ua04R1uExyyzi-bcKj4D80jO&index=8
    - SourceCode : https://github.com/Vishulucky/RetrofitExample

## Mqtt
  - https://medium.com/@gaikwadchetan93/android-real-time-communication-using-mqtt-9ea42551475d
  - https://androidkt.com/android-mqtt/

## Jetpack Compose
  - PlayList: https://www.youtube.com/watch?v=tl8RLM6Sy9s&list=PL4EnMCc01RC0B9kmeZq7xUGpd0wlQkd40&index=1

## Testing
  - PlayList: https://www.youtube.com/playlist?list=PL4EnMCc01RC0F5CMo9X65gbShqloMGlc2


# Interview Questions:
  - What is ktx : https://blog.mindorks.com/android-ktx-android-development-with-kotlin
  
  - HTTP Caching: 
    - https://www.journaldev.com/23297/android-retrofit-okhttp-offline-caching
    - https://medium.com/@bapspatil/caching-with-retrofit-store-responses-offline-71439ed32fda
    
  - How to make a global error class for Retrofit errors:
    - https://futurestud.io/tutorials/retrofit-2-catch-server-errors-globally-with-response-interceptor

  - ListView vs RecyclerView: https://medium.com/@kish.imss/listview-vs-recyclerview-2965d50b363

  - ConstraintLayout Barrier vs Guideline
    - https://stackoverflow.com/questions/47114672/what-is-difference-between-barrier-and-guideline-in-constraint-layout
    - https://riggaroo.dev/constraintlayout-guidelines-barriers-chains-groups/

  - How to update observer using livedata only once: https://blog.mindorks.com/observe-event-only-once-using-single-live-event
 
  - Livedata vs MutableLiveData : 
    - MutableLiveData is a LiveData object whose value can be changed. MutableLiveData is a generic class, so you need to specify the type of data     that it holds. To change the       value of the data held by the LiveData , use the setValue() method on the LiveData variable.

  - Set Value vs Post value : https://blog.mindorks.com/livedata-setvalue-vs-postvalue-in-android
  
  - Can arraylist size be defined and default size: https://www.geeksforgeeks.org/how-to-increase-the-capacity-size-of-arraylist/

  - Continuous integration tools: Jenkins/Sonar[Code review]
  - Android Profilers

# What's new
 - Android jetpack compose.
 - Pref data source.


